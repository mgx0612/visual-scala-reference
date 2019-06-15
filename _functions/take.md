---
title: take
layout: function
permalink: /take
---

# `take`

~~~ scala
trait Collection[A] {
  def take(i: Int): Collection[A]
}
~~~

`take` creates a collection by keeping the first `i` elements of this collection and discarding the rest.

<figure class="diagram">
  <img src="images/take.svg" alt="take function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>