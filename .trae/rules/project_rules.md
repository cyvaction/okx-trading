1. 程序已经启动，并且使用rebel自动编译，不需要频繁重启
2. 程序启动后不要在原终端上执行命令，会kill掉程序
3. 如果是修改接口，每次修改完接口后，尝试调用接口验证结果是否准确，不准确继续修改
4. 禁止使用powershell，会导致乱码，使用git bash
5. 调用方式  curl -X POST http://localhost:8088/api/api/backtest/ta4j/generate-strategy   -H "Content-Type: application/json; "   -d '"生成类似atr的策略"'