前言: 在春招的时候，面了几家企业，但是由于不懂的如何如何准备，基本都以失败告终。在面试的过程中，经常遇到的尴尬事情就是，当被问到某个问题以考察相关知识点的时候，明明自己是学过的，但是却无法很完整的回答，或是无法很好的将自己知道的表达出来。究其原因：没有对自己学过的知识进行体系性的整理，而前端开发整个体系又非常的庞大，在不断的学习确实容易遗忘之前学过的知识，而在自己想要进行回顾的时候也面临着不知从而下手的问题。因此这使我产生了，在学习复习的过程中对知识进行系统性的整理，以使得知识更加的牢固，回顾的时候也能事半功倍，当然为了整理也使得自己去思考知识点之间的联系，每个知识点具有怎样的特性，使得记忆更加的深刻。

整理的方式，主要有两点一是api的整理，二是理解型备注。将api再细致分类，例如数组api根据操作的目的进行分类,如对堆栈的操作，遍历操作，分类后在进行思考某一类对是否会改变原有数组对象，以及是否产生新的数组对象的相关规律；理解性备注：如对继承模式的归纳整理，通过树状图形式可以很快get到有哪些继承方式，而自己也进一步在get到多少种方式的情况下，用摘录或自己总结的方式备注要每种方式的特点，以及还存在的不足。例如:借用构造函数式通过apply函数的特性来实现的但不足是无法进行某些属性方法的共享，原型链继承，则是通过原型链的概念，访问特性来实现，但不足是所有一切都共享，而组合式继承则结合两种继承的优点，使得子类既能让子类实例具有自己特有的属性方法，又能共享某些属性和方法。但依旧有不足，体现在父类构造函数执行了两次，于是有了寄生组合式继承，而寄生具有的特点就是在返回对象前在内部根据需要进行了一定的处理。最后就是原型是继承，其核心特点在Object.create这个方法中都表现出来了，需要注意的点则是引用类型的共用，然后就是寄生式继承，这种方式是在原型式继承的方式上进行了一些增强处理。当然如果看到这些还不能回忆起来，那就该回去翻书了。有些api也会注明在书本的哪页以方便回去翻书。


以下是从整理的思维导图中导出的一个最完整的图片，有点点大;
之后会再按类别拆分成小的图片，也会将思维导图中的知识点文字导出来。（最近还在跑秋招，时间比较紧，所以还请期待）
