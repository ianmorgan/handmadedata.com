---
layout: post
tags:   scala functional-programming
disqus: false 
---

# Explaining a monad in 10 steps

## Step 1 - Categories 

Monads come from Category Theory. Categories are just containers with a set of common behaviours 
that should be true for all types and values. Of course formally proving they work for anything may be 
difficult, but in the real world we can normally rely upon intuition and common sense to decide what 
is good category. A list is a classic example.

{% highlight scala %}
scala > val names = List("John", "Paul", "Ringo", "George")
names: List[java.lang.String] = List(John, Paul, Ringo, George)

scala> names.size
res0: Int = 4
{% endhighlight %}


fghf

## Step 2 - Changing data in our categories 

Our containers are values, that is they are immutable 

  A  ->  B
         |


"<a href="http://commons.wikimedia.org/wiki/File:Commutative_diagram_for_morphism.svg#mediaviewer/File:Commutative_diagram_for_morphism.svg">Commutative diagram for morphism</a>" by <a href="//commons.wikimedia.org/wiki/User:Cepheus" title="User:Cepheus">User:Cepheus</a> - Own work, based on <a href="//en.wikipedia.org/wiki/Image:MorphismComposition-01.png" class="extiw" title="en:Image:MorphismComposition-01.png">en:Image:MorphismComposition-01.png</a>. Licensed under Public domain via <a href="//commons.wikimedia.org/wiki/">Wikimedia Commons</a>.
         
<img  src="http://upload.wikimedia.org/wikipedia/commons/1/1a/MorphismComposition-01.png"> 

en:Image:MorphismComposition-01.png">
