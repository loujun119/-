1. Material-UI:
   https://material-ui.com/

2. npm ラボラトリー管理
   https://www.npmjs.com/package/typescript

3. yarn ラボラトリー管理
   https://classic.yarnpkg.com/en/package/connected-react-router

4. node.js
   http://nodejs.cn/learn/the-package-json-guide
   https://blog.csdn.net/CEZLZ/article/details/108100460
   https://blog.csdn.net/qq_39953537/article/details/109256826

5. redux-saga
   https://redux-saga.js.org/

6. redux-ToolKit
   https://redux-toolkit.js.org/introduction/getting-started
   https://codesandbox.io/s/mfetp?file=/src/store.js
   https://viblo.asia/p/redux-toolkit-redux-saga-Ljy5VPAVZra

7. ES6
   https://es6.ruanyifeng.com/

8. javascript
   https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/A_re-introduction_to_JavaScript
   https://wangdoc.com/javascript/basic/grammar.html

9. wijmo flex grid
   https://demo.grapecity.com.cn/wijmo/demos/Grid/Overview/react
   https://www.grapecity.com/wijmo/api/modules/wijmo_grid.html
   https://www.grapecity.com/wijmo/demos/Input/Menu/Overview

10. Axios
    http://www.axios-js.com/zh-cn/docs/#axios-request-config
    https://blog.csdn.net/fuckthebugs/article/details/105775579

11. markdown
    https://www.markdown.xyz/getting-started/
    https://www.mdxjs.cn/guides/terminal

12. docusaurus
    https://www.docusaurus.cn/
    https://www.wenjiangs.com/doc/zmauaesd

13. performance
    https://zenn.dev/nash/articles/df6011609bdd34
    https://zenn.dev/irico/articles/acafb8bc7fb7f7
    https://qiita.com/hellokenta/items/6b795501a0a8921bb6b5
    https://qiita.com/teradonburi/items/5b8f79d26e1b319ac44f.

14. mock
    https://github.com/safak/youtube2022/tree/react-testing
    https://www.youtube.com/watch?v=oMv2eAGWtZU
    https://github.com/mswjs/examples/tree/master/examples/with-redux-saga

    https://github.com/CodingWith-Adam/react-test-fetch-api-call-with-msw

15. react query
    https://cangsdarm.github.io/react-query-web-i18n/guides&concepts/infinite-queries
    https://react-query.tanstack.com/reference/useInfiniteQuery
    https://github.com/mswjs/data#querying-data
    https://blog.logrocket.com/pagination-infinite-scroll-react-query-v3/
    https://www.youtube.com/watch?v=4jMAnIIEI3M
    https://github.com/weibenfalk/react-query-week/tree/main/5-react-query-useInfiniteQuery
    https://www.bilibili.com/video/BV1pD4y1c7Wu?from=search&seid=13921733379838544052&spm_id_from=333.337.0.0&vd_source=d46c2fd8bede7d80a5f25efb11e5704a

    API: ...reviews?limit=5&page=1
    DB: page=1;
        const prePageLastNumber = page * limit;
        const reviewList = ...
        const prePageLastReviewId = reviewList[prePageLastNumber - 1].id
    {
      page: 1,
      total_page: 3
      result: {data}
    }
    余数: a % b = 0 没有余数,整除