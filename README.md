## 欢迎来到留言版

你可以在这里添加你的留言。

<link rel="stylesheet" href="https://unpkg.com/gitalk/dist/gitalk.css">
<script src="https://unpkg.com/gitalk/dist/gitalk.min.js"></script>
<div id="gitalk-container"></div>
<script>
  const gitalk = new Gitalk({
    clientID: 'f09cf52948d43f4adac1',
    clientSecret: 'bc6ca7b09a9f79e97efb995b32265539fa826b0d',
    repo: 'board',
    owner: 'mandy719',
    admin: ['mandy719'],
    id: location.pathname,
    distractionFreeMode: false
  })

  gitalk.render('gitalk-container')
</script>
