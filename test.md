---
description: 'https://rules.sonarsource.com/java/tag/tests'
---

# Test



## Test

1. 断言应该完整
2. 测试应该包含断言
3. JUnit test case应该调用超类方法
4. TestCases应该包含测试
5. 不应该比较类型不兼容的声明
6. JUnit5的内部测试类应该用@Nested注解
7. 测试受检异常时候期望仅仅调用一个方法
8. 在捕获错误的try-catch的try块中不应使用断言方法
9. 应该避免Mock一个类的所有非私有方法
10. 开始JUnit4的方法setUp\(\)和tearDown\(\)应该正确使用注解
11. JUnit断言不应该在”run“方法中使用
12. 测试方法不应该使用有竞争关系的注解
13. 断言不应该和自己比较
14. 设置断言上下文的AssertJ方法应在断言之前出现
15. AssertJ配置应该被apply
16. JUnit5的类和方法不应该被悄悄忽略
17. 相同的测试应该分组到一个单一参数化测试
18. 测试应该稳定
19. 测试方法不应该包含太多断言
20. AssertJ 的“assertThatThrownBy"不应该单独使用
21. JUnit assertTrue / assertFalse应该简化为对应的专用断言
22. 测试运行时异常时，仅应调用一种方法
23. 通过JUnit ExpectedException规则进行的异常测试不应与其他断言混合使用
24. 断言参数应该传递正确
25. “Thread.sleep\(\)”不应该在测试中使用
26. JUnit4 @Ignored和JUnit5 @Disabled注解应该被用作禁止测试和应该提供理由
27. AssertJ断言“allMatch”和“doesNotContains”也应测试是否为空
28. 连续的AssertJ “assertThat”语句应链接在一起
29. 链式的AssertJ的断言应该被简化为对应的专用断言
30. 通过JUnit的@Test的异常测试应该被禁止
31. 测试类应该遵循命名规范
32. JUnit的Rule应该被使用
33. JUnit5的测试类和测试方法应该拥有包级可见访问权限
34. 测试应该使用固定的数据而不是随机的数据
35. 应该使用Spring的ModelAndViewAssert断言而不是其他。
36. 单元测试应该抛出异常
37. 测试方法应符合命名约定
38. 断言中不应使用字面布尔值和空值
39. 测试断言应该包含信息
40. 将测试从JUnit4迁移到新的JUnit5注解

