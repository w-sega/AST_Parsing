### AST_Parsing
AST_Parsing为[Parsing](https://github.com/w-sega/Parsing)精简版  
利用抽象语法树 (AST) 对当前页面加载的 Js 进行深度静态分析。能识别出代码中的 API 接口调用（如 fetch, axios 等）及其使用的参数，即使代码经过了 Webpack 打包或混淆。通过 AST 优先筛选，仅将最有价值的代码片段提交给 AI 分析，显著节省 AI token 消耗并提升效率。
