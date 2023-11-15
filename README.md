<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>个人博客</title>
  <!-- 引入 Bootstrap 样式 -->
  <link rel="stylesheet" href="https://cdn.bootcdn.net/ajax/libs/twitter-bootstrap/4.5.3/css/bootstrap.min.css">
  <!-- 引入自定义样式 -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">个人博客</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#">首页</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">文章</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">关于</a>
        </li>
      </ul>
    </div>
  </nav>

  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <div class="card mb-3">
          <img src="https://via.placeholder.com/800x400.png?text=Article+Image" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">文章标题</h5>
            <p class="card-text">文章内容</p>
            <p class="card-text"><small class="text-muted">发布时间：2022-01-01</small></p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card mb-3">
          <div class="card-body">
            <h5 class="card-title">关于我</h5>
            <p class="card-text">这里是关于我</p>
          </div>
        </div>
        <div class="card mb-3">
          <div class="card-body">
            <h5 class="card-title">最新文章</h5>
            <ul class="list-unstyled">
              <li><a href="#">文章标题1</a></li>
              <li><a href="#">文章标题2</a></li>
              <li><a href="#">文章标题3</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- 引入 jQuery 和 Popper.js -->
  <script src="https://cdn.bootcdn.net/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  <script src="https://cdn.bootcdn.net/ajax/libs/popper.js/2.10.2/umd/popper.min.js"></script>
  <!-- 引入 Bootstrap 核心 JavaScript -->
  <script src="https://cdn.bootcdn.net/ajax/libs/twitter-bootstrap/4.5.3/js/bootstrap.min.js"></script>
</body>
</html>
