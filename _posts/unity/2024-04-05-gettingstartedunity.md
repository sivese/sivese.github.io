---
layout: post
title: "Unity의 UI 시스템과 개요"
date: 2024-04-06
categories: Unity
tag: [ Basic, UI ]
---

## Introduction

Unity가 지금처럼 년식이 아닌 버전 넘버를 붙이던 시절엔 지금같이 매우 폭넓은 기능을 지원하지는 않았다. 단지 높은 생산성과 가벼움으로 모바일 개발쪽으로 각광받은 정도였다. 그렇지만 지금은 명실상부한 메이저 게임엔진으로 자리를 잡았고, 그 기능도 매우 많아져서 유니티로 할 수 있는 것도 많다. 그래서 유니티의 기초를 주제로 해서 다룰려고 해도 그 내용이 상당히 방대하다.

몇 몇 소수의 케이스가 있긴하지만, UI가 없는 게임은 없다. 그래서 무엇부터 다뤄볼까 하다가 UI부터 출발해보기로 했다. 이 포스팅은 내 참회록 겸해서 시작하는 것이기도 해서 이전의 Humble Bundle에서 샀던 책들과 Unity의 Manual을 바탕으로 다룰 생각이다. 내용은 최대한 최신으로 다룰 생각이고, 책 내용도 같이 다루다보니 아무래도 중구난방이 될 수도 있다. 그렇지만 진행해봐야 하지 않겠나.

{% highlight csharp %}
class Unit : MonoBehaviour
{
    void Start()
    {

    }

    void Update()
    {
        
    }
}
{% endhighlight %}