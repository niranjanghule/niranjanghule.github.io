---
title: Proxy Design Pattern In Java
date: 2022-05-22
categories: [Software Development, Design Patterns]
tags: [proxy pattern]
---

## Let's make a Voting App for Singing Competition

![Singing Voting App](/assets/img/iivote.jpeg)
_Voting App_

Let's suppose you are working on Voting software which provides facility to users to vote
for their favourite contenstants in a singing competition.

Your design is based on an Interface Contestant which has following structure:

```java
public interface Contestant{

    int getScore();
    String getName();
    int getTotalVotes();
    
    void setScore();
    void setName();
    void vote();

}
```

## The Contestant Implementation

```java
public class Contestant {

    private String name;
    private int totalVotes = 0;
    private int score = 0;

    public Contestant(String name){
        this.name = name;
    }

    public String getName() {
        return name;
    }

    public int getTotalVotes() {
        return totalVotes;
    }

    public int getScore() {
        return score;
    }

    public void setName(String name) {
        this.name = name;
    }

    public void vote() {
        this.totalVotes++;
    }

    public void setScore(int score) {
        this.score += score;
    }
}
```
## A closer look at implementation

![contestant implementation](/assets/img/implementation.jpg)
_Contestant Implementation_

![complaint](/assets/img/complaint.jpg){: .shadow }


Well, we can't find out if he really has no more friends left.
However there seems to be a problem with our implementation.
