---
layout: post
title: "Rust General Concepts"
date: 2024-04-01 01:58
categories: Rust 
tag: [ Basic ]
---

### Variable and Mutability

보통 우리가 마주하는 대부분의 프로그래밍 언어에서 변수들은 언제든지 값을 변경할 수 있는 상태다. 이 때문에 기본적으로 가변상태라고 할 수 있다. 하지만 러스트는 이와는 반대로 기본적으로 불변상태로 변수를 선언한다. 이 때문에 중간에 값을 변경하고자 한다면 가변 상태를 별도로 지정해주어야 한다. 이에 대한 설명은 다음 코드를 보면 이해가 더 빠를 것이다.

```
    let num = 10;
    num = 15; //Compile error!

    let mut mut_num = 15;
    mut_num = 10; //it's okay
```