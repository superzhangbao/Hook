# Hook

Hook View的OnClickListenr
1.Hook 的选择点：静态变量和单例，因为一旦创建对象，它们不容易变化，非常容易定位。
2.Hook 过程：
      (1).寻找 Hook 点，原则是静态变量或者单例对象，尽量 Hook public 的对象和方法。
      (2).选择合适的代理方式，如果是接口可以用动态代理。
      (3).偷梁换柱——用代理对象替换原始对象。
