# github-action-test

该项目使用 JUnit 5 进行单元测试并通过 GitHub Actions 持续集成。

更新说明：
- 修复 `MainTest` 中的断言错误，将 `add(1, 1)` 的期望值改为 `2`，与 `Main.add(a, b)` 的实现一致。

运行测试（本地需安装 Maven）：
- 在项目根目录执行 `mvn test`