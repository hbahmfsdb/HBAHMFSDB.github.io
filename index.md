---
layout: default
---



<script>
    // 页面加载时默认显示“学术活动”
    document.addEventListener('DOMContentLoaded', function() {
      loadContent('portfolio');
    });
  
    // 切换内容的函数
    function loadContent(sectionId) {
      // 隐藏所有内容块
      const sections = ['portfolio', 'timeline', 'join', 'team', 'teacher', 'about'];
      sections.forEach(id => {
        const el = document.getElementById(id + '-content');
        if (el) el.style.display = 'none';
      });
  
      // 显示目标块
      const target = document.getElementById(sectionId + '-content');
      if (target) {
        target.style.display = 'block';
      }
    }
  </script>


  <body id="page-top">

        <!-- Navigation -->
<nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
    <div class="container">
      <a class="navbar-brand js-scroll-trigger" href="#page-top">重庆工程学院计创中心</a>
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        Menu
        <i class="fas fa-bars"></i>
      </button>
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav text-uppercase ml-auto">
          <li class="nav-item"><a class="nav-link" href="#" onclick="loadContent('portfolio'); return false;">学术活动</a></li>
          <li class="nav-item"><a class="nav-link" href="#" onclick="loadContent('timeline'); return false;">荣誉墙</a></li>
          <li class="nav-item"><a class="nav-link" href="#" onclick="loadContent('join'); return false;">加入我们</a></li>
          <li class="nav-item"><a class="nav-link" href="#" onclick="loadContent('team'); return false;">闪耀成员</a></li>
          <li class="nav-item"><a class="nav-link" href="#" onclick="loadContent('teacher'); return false;">优秀指导老师</a></li>
          <li class="nav-item"><a class="nav-link" href="#" onclick="loadContent('about'); return false;">关于我们</a></li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- End Navigation -->
  
  <!-- Header -->
  
  <header class="masthead">
    <div class="container">
      <div class="intro-text"><div class="intro-lead-in"><p>欢迎来到我们工作室！</p>
</div><div class="intro-heading text-uppercase">
  <!-- <p>It’s Nice To Meet You</p> -->
</div><a class="btn btn-primary btn-xl text-uppercase js-scroll-trigger" href="#services">Tell Me More</a></div>
    </div>
  </header>
  
  <!-- End Header -->
   <!-- 主内容区容器 -->
<div id="content-area">
    <!-- 这里会动态加载内容 -->
    <!-- 默认显示 portfolio -->
    <section class="page-section" id="portfolio-content">
        <div class="container">
            <div class="row">
              <div class="col-lg-12 text-center">
                <h2 class="section-heading text-uppercase"><p>比赛介绍</p>
        </h2>
                <h3 class="section-subheading text-muted"><p>Lorem ipsum dolor sit amet consectetur.</p>
        </h3>
              </div>
            </div>
            <div class="row">
            
              <div class="col-md-4 col-sm-6 portfolio-item">
                <a class="portfolio-link" data-toggle="modal" href="#p1">
                  <div class="portfolio-hover">
                    <div class="portfolio-hover-content">
                      <i class="fas fa-plus fa-3x"></i>
                    </div>
                  </div>
                  <img class="img-fluid" src="C:\Users\ccc\project_1\assets\img\active\挑战杯.png" alt="">
                </a>
                <div class="portfolio-caption">
                  <h4>挑战杯全国大学生系列科技学术竞赛</h4>
                  <p class="text-muted">subtitle</p>
                </div>
              </div>
            
              <div class="col-md-4 col-sm-6 portfolio-item">
                <a class="portfolio-link" data-toggle="modal" href="#p2">
                  <div class="portfolio-hover">
                    <div class="portfolio-hover-content">
                      <i class="fas fa-plus fa-3x"></i>
                    </div>
                  </div>
                  <img class="img-fluid" src="C:\Users\ccc\project_1\assets\img\active\机器人与人工智能大赛.png" alt="">
                </a>
                <div class="portfolio-caption">
                  <h4>中国机器人及人工智能大赛</h4>
                  <p class="text-muted">Illustration</p>
                </div>
              </div>
            
              <div class="col-md-4 col-sm-6 portfolio-item">
                <a class="portfolio-link" data-toggle="modal" href="#p3">
                  <div class="portfolio-hover">
                    <div class="portfolio-hover-content">
                      <i class="fas fa-plus fa-3x"></i>
                    </div>
                  </div>
                  <img class="img-fluid" src="C:\Users\ccc\project_1\assets\img\active\互联网+.jpg" alt="">
                </a>
                <div class="portfolio-caption">
                  <h4>中国国际大学生创新大赛</h4>
                  <p class="text-muted">Graphic Design</p>
                </div>
              </div>
            
            </div>
          </div>
      <div class="container">...</div>
    </section>
    <div
  class="portfolio-modal modal fade"
  id="p1"
  tabindex="-1"
  role="dialog"
  aria-hidden="true"
>
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="close-modal" data-dismiss="modal">
        <div class="lr">
          <div class="rl"></div>
        </div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-lg-8 mx-auto">
            <div class="modal-body">
              <!-- Project Details Go Here -->
              <h2 class="text-uppercase">挑战杯全国大学生系列科技学术竞赛</h2>
              <p class="item-intro text-muted">“挑战杯”是全国大学生最高水平的科技创新竞技场！在这里，创意与智慧交融，梦想与实践同行。
                我们鼓励每一位成员勇敢参赛，用科技探索未知，用创新点亮未来。每一次挑战，都是一次成长；每一份作品，都是青春的见证。</p>
              <img
                class="img-fluid d-block mx-auto"
                src="C:\Users\ccc\project_1\assets\img\active\挑战杯.png"
                alt="image alt text"
              />
              <p><p>Use this area to describe your project. <strong>Markdown</strong> supported.</p>

<p>optional info list (delete if not using):</p>

<ul class="list-inline">
  <li>Date:</li>
  <li>Client:</li>
  <li>Category:</li>
</ul>

</p>
              <button
                class="btn btn-primary"
                data-dismiss="modal"
                type="button"
              >
                <i class="fas fa-times"></i>
                关闭
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 2 -->

<div
  class="portfolio-modal modal fade"
  id="p2"
  tabindex="-1"
  role="dialog"
  aria-hidden="true"
>
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="close-modal" data-dismiss="modal">
        <div class="lr">
          <div class="rl"></div>
        </div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-lg-8 mx-auto">
            <div class="modal-body">
              <!-- Project Details Go Here -->
              <h2 class="text-uppercase">Project Threads</h2>
              <p class="item-intro text-muted">subtitle lorem ipsum dolor sit amet consectetur.</p>
              <img
                class="img-fluid d-block mx-auto"
                src="C:\Users\ccc\project_1\assets\img\active\机器人与人工智能大赛.png"
                alt="Shirts on a hanger"
              />
              <p><p>Use this area to describe your project. <strong>Markdown</strong> supported. This entry (project1.md) uses links for the image sources. All other projects in the portfolio use local images. Both work just fine! Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>

<ul class="list-inline">
  <li>Date: January 2017</li>
  <li>Client: Threads</li>
  <li>Category: Illustration</li>
</ul>
</p>
              <button
                class="btn btn-primary"
                data-dismiss="modal"
                type="button"
              >
                <i class="fas fa-times"></i>
                关闭
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 3 -->

<div
  class="portfolio-modal modal fade"
  id="p3"
  tabindex="-1"
  role="dialog"
  aria-hidden="true"
>
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="close-modal" data-dismiss="modal">
        <div class="lr">
          <div class="rl"></div>
        </div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-lg-8 mx-auto">
            <div class="modal-body">
              <!-- Project Details Go Here -->
              <h2 class="text-uppercase">Project Name</h2>
              <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>
              <img
                class="img-fluid d-block mx-auto"
                src="C:\Users\ccc\project_1\assets\img\active\互联网+.jpg"
                alt="Keep Exploring"
              />
              <p><p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>

<ul class="list-inline">
  <li>Date: January 2017</li>
  <li>Client: Explore</li>
  <li>Category: Graphic Design</li>
</ul>
</p>
              <button
                class="btn btn-primary"
                data-dismiss="modal"
                type="button"
              >
                <i class="fas fa-times"></i>
                关闭
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

    
  
    <section class="page-section" id="timeline-content" style="display: none;">
        <div class="container">
            <div class="row">
              <div class="col-lg-12 text-center">
                <h2 class="section-heading text-uppercase"><p>展出荣誉</p>
        </h2>
                <h3 class="section-subheading text-muted">展出属于我们的荣耀</h3>
              </div>
            </div>
            <div class="row">
              <div class="col-lg-12">
                <ul class="timeline">
                      <li>
                    <div class="timeline-image">
                      <img class="rounded-circle img-fluid" src="assets/img/timeline/1.jpg" alt="">
                    </div>
                    <div class="timeline-panel">
                      <div class="timeline-heading">
                        <h4><p>2009-2011</p>
        </h4>
                        <h4 class="subheading">Our Humble Beginnings</h4>
                      </div>
                      <div class="timeline-body">
                        <div class="text-muted"><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt ut voluptatum eius sapiente, totam reiciendis temporibus qui quibusdam, recusandae sit vero unde, sed, incidunt et ea quo dolore laudantium consectetur!</p>
        </div>
                      </div>
                    </div>
                  </li>
            
                      <li class="timeline-inverted">
                    
                  <div class="timeline-image">
                      <img class="rounded-circle img-fluid" src="assets/img/timeline/2.jpg" alt="">
                    </div>
                    <div class="timeline-panel">
                      <div class="timeline-heading">
                        <h4><p>March 2011</p>
        </h4>
                        <h4 class="subheading">An Agency is Born</h4>
                      </div>
                      <div class="timeline-body">
                        <div class="text-muted"><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt ut voluptatum eius sapiente, totam reiciendis temporibus qui quibusdam, recusandae sit vero unde, sed, incidunt et ea quo dolore laudantium consectetur!</p>
        </div>
                      </div>
                    </div>
                  </li>
            
                      <li>
                    <div class="timeline-image">
                      <img class="rounded-circle img-fluid" src="assets/img/timeline/3.jpg" alt="image alt text">
                    </div>
                    <div class="timeline-panel">
                      <div class="timeline-heading">
                        <h4><p>2019</p>
        </h4>
                        <h4 class="subheading">Jekyll Theme is created</h4>
                      </div>
                      <div class="timeline-body">
                        <div class="text-muted"><p>Ravi Riley converted Agency, a Bootstrap-based theme, into a Jekyll theme. The Jekyll theme can be installed as a Ruby gem, or remotely. For more information, visit the documentation.</p>
        </div>
                      </div>
                    </div>
                  </li>
            
                      <li class="timeline-inverted">
                    
                  <div class="timeline-image">
                      <img class="rounded-circle img-fluid" src="assets/img/timeline/4.jpg" alt="">
                    </div>
                    <div class="timeline-panel">
                      <div class="timeline-heading">
                        <h4><p>2009-2011</p>
        </h4>
                        <h4 class="subheading">Title</h4>
                      </div>
                      <div class="timeline-body">
                        <div class="text-muted"><p>Your description here, <strong>Markdown</strong> is fully supported.</p>
        </div>
                      </div>
                    </div>
                  </li>
              
                  
              
            <li class="timeline-inverted">
                    <div class="timeline-image">
                      <h4>期待你的<br> 加入增添 <br>更多荣誉</h4>
                    </div>
                  </li>
            
        
                </ul>
              </div>
            </div>
          </div>
    </section>
  
    <section class="page-section" id="join-content" style="display: none;">
        <div class="container">
            <div class="text-center">
                <h2 class="section-heading text-uppercase">加入我们</h2>
                <h3 class="section-subheading text-muted">探索我们工作室的精彩瞬间！</h3>
                <hr style="margin: 2px auto; border: 1px solid black; width: 90%; max-width: 700px;">
            </div>
            <div class="text-center">
              <h2 class="section-heading text-uppercase"></h2>
            </div>
            <div class="row">
                <!-- 1 -->
                <div class="col-lg-4 col-sm-6 mb-4">
                    <div class="portfolio-item">
                        <a class="portfolio-link" data-bs-toggle="modal" href="#eventModal1">
                            <img class="img-fluid" src="../assets/img/active/前端开发.jpg" alt="前端开发" />
                        </a>
                        <div class="portfolio-caption">
                            <div class="portfolio-caption-heading">前端开发</div>
                            <div class="portfolio-caption-subheading text-muted">11111111</div>
                        </div>
                    </div>
                </div>
                <!-- 2 -->
                <div class="col-lg-4 col-sm-6 mb-4">
                    <div class="portfolio-item">
                        <a class="portfolio-link" data-bs-toggle="modal" href="#eventModal2">
                            <img class="img-fluid" src="../assets/img/active/后端开发.jpeg" alt="后端开发" />
                        </a>
                        <div class="portfolio-caption">
                            <div class="portfolio-caption-heading">后端开发</div>
                            <div class="portfolio-caption-subheading text-muted">1111111111</div>
                        </div>
                    </div>
                </div>
                <!-- 3 -->
                <div class="col-lg-4 col-sm-6 mb-4">
                    <div class="portfolio-item">
                        <a class="portfolio-link" data-bs-toggle="modal" href="#eventModal3">
                            <img class="img-fluid" src="../assets/img/active/全栈开发.jpg" alt="全栈开发" />
                        </a>
                        <div class="portfolio-caption">
                            <div class="portfolio-caption-heading">全栈开发</div>
                            <div class="portfolio-caption-subheading text-muted">2222222</div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-sm-6 mb-4">
                    <div class="portfolio-item">
                        <a class="portfolio-link" data-bs-toggle="modal" href="#eventModal3">
                            <img class="img-fluid" src="../assets/img/active/嵌入式.jpg" alt="嵌入式" />
                        </a>
                        <div class="portfolio-caption">
                            <div class="portfolio-caption-heading">嵌入式技术</div>
                            <div class="portfolio-caption-subheading text-muted">2222222</div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-sm-6 mb-4">
                  <div class="portfolio-item">
                      <a class="portfolio-link" data-bs-toggle="modal" href="#eventModal4">
                          <img class="img-fluid" src="../assets/img/active/算法.webp" alt="算法" />
                      </a>
                      <div class="portfolio-caption">
                          <div class="portfolio-caption-heading">算法</div>
                          <div class="portfolio-caption-subheading text-muted">3</div>
                      </div>
                  </div>
              </div>
              <div class="col-lg-4 col-sm-6 mb-4">
                <div class="portfolio-item">
                    <a class="portfolio-link" data-bs-toggle="modal" href="#eventModal4">
                        <img class="img-fluid" src="../assets/img/active/大模型.webp" alt="大模型" />
                    </a>
                    <div class="portfolio-caption">
                        <div class="portfolio-caption-heading">AI大模型技术</div>
                        <div class="portfolio-caption-subheading text-muted">3</div>
                    </div>
                </div>
            </div>
            </div>
        </div>
    </section>
    <!-- 闪耀的成员 -->
    <section class="page-section" id="team-content" style="display: none;">
        <div class="container">
          <div class="row">
            <div class="col-lg-12 text-center">
              <h2 class="section-heading text-uppercase">闪耀的成员</h2>
              <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
            </div>
          </div>
          <div class="row d-flex justify-content-center">
          
            <div class="col-sm-4">
              <div class="team-member">
                <img class="mx-auto rounded-circle" src="assets/img/team/zhangtao.png" alt="">
                <h4>张涛</h4>
                <p class="text-muted">就业单位：北京交通大学 晓多科技</p>
            <p class="text-muted">研究方向：多模态大模型增强检索技术 多智能体协同</p>
                <ul class="list-inline social-buttons">
                
                  <li class="list-inline-item">
                <a href="https://github.com/1692775560">
                  <i class="fab fa-github"></i>
                </a>
              </li>
                
                
                </ul>
              </div>
            </div>
        
        
          
            <div class="col-sm-4">
              <div class="team-member">
                <img class="mx-auto rounded-circle" src="assets/img/team/500x500.jpg" alt="">
                <h4>Diana Perterson</h4>
                <p class="text-muted">Lead Developer</p>
                <ul class="list-inline social-buttons">
                
                  <li class="list-inline-item">
                    <a href="https://twitter.com">
                      <i class="fab fa-twitter"></i>
                    </a>
                  </li>
                
                  <li class="list-inline-item">
                    <a href="https://facebook.com">
                      <i class="fab fa-facebook-f"></i>
                    </a>
                  </li>
                
                  <li class="list-inline-item">
                    <a href="https://linkedin.com">
                      <i class="fab fa-linkedin-in"></i>
                    </a>
                  </li>
                
                </ul>
              </div>
            </div>
          
          </div>
          <div class="row">
            <div class="col-lg-8 mx-auto text-center">
              <div class="large text-muted"><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut eaque, laboriosam veritatis, quos non quis ad perspiciatis, totam corporis ea, alias ut unde. <strong>Markdown</strong> supported.</p>
        </div>
            </div>
          </div>
        </div>
        </section>
        <!-- 优秀指导老师 -->

       <!-- 优秀指导老师 -->
<section class="page-section" id="teacher-content" style="display: none;">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 text-center">
          <h2 class="section-heading text-uppercase">优秀指导老师</h2>
          <h3 class="section-subheading text-muted">他们用智慧点亮创新之路，用热情点燃学生梦想</h3>
        </div>
      </div>
      <div class="row d-flex justify-content-center">
        
        <!-- 老师1 -->
        <div class="col-sm-4">
          <div class="team-member">
            <img class="mx-auto rounded-circle" src="assets/img/teachers/liwei.png" alt="李伟老师">
            <h4>李伟</h4>
            <p class="text-muted">职称：副教授 | 研究方向：人工智能与智能系统</p>
            <p class="text-muted">指导成果：连续5年带领学生获“挑战杯”国家级奖项</p>
            <ul class="list-inline social-buttons">
              <li class="list-inline-item">
                <a href="mailto:liwei@cqie.edu.cn">
                  <i class="fas fa-envelope"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="https://scholar.google.com/cn" target="_blank">
                  <i class="fas fa-graduation-cap"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
  
        <!-- 老师2 -->
        <div class="col-sm-4">
          <div class="team-member">
            <img class="mx-auto rounded-circle" src="assets/img/teachers/zhaoming.png" alt="赵明老师">
            <h4>赵明</h4>
            <p class="text-muted">职称：教授 | 研究方向：大数据与云计算</p>
            <p class="text-muted">教学理念：以赛促学，以研促教，培养创新型人才</p>
            <ul class="list-inline social-buttons">
              <li class="list-inline-item">
                <a href="mailto:zhaoming@cqie.edu.cn">
                  <i class="fas fa-envelope"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="https://researchgate.net" target="_blank">
                  <i class="fas fa-graduation-cap"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
  
        <!-- 老师3 -->
        <div class="col-sm-4">
          <div class="team-member">
            <img class="mx-auto rounded-circle" src="assets/img/teachers/wangfang.jpg" alt="王芳老师">
            <h4>王芳</h4>
            <p class="text-muted">职称：讲师 | 研究方向：人机交互与用户体验</p>
            <p class="text-muted">曾指导学生获“互联网+”大赛全国金奖</p>
            <ul class="list-inline social-buttons">
              <li class="list-inline-item">
                <a href="mailto:wangfang@cqie.edu.cn">
                  <i class="fas fa-envelope"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="https://linkedin.com" target="_blank">
                  <i class="fab fa-linkedin-in"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
  
      </div>
      <div class="row">
        <div class="col-lg-8 mx-auto text-center">
          <p class="large text-muted">
            我们的指导老师不仅是知识的传授者，更是创新路上的引路人。他们无私奉献，悉心指导，助力每一位学生成长为卓越的科技人才。
          </p>
        </div>
      </div>
    </div>
  </section>

    <!-- About -->

    <section class="page-section" id="about-content" style="display: none;">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 text-center">
          <h2 class="section-heading text-uppercase">关于我们</h2>
          <h3 class="section-subheading text-muted">我们的故事</h3>
        </div>
      </div>
      <div>
        
      </div>
      <div class="row">
        <div class="col-lg-8 mx-auto text-center">
          <div class="large text-muted">
            <p>在数字时代，技术革新日新月异，为了激发学生的创造力、培养其解决实际问题的能力，学校成立了计算机应用创新中心。
              本中心旨在为全校师生提供一个开放、协作的环境，促进信息技术的应用与创新。</p>
            <p>无论你是初学者还是有经验的开发者，只要你对计算机技术和创新充满热情，
            我们都欢迎你的加入！在这里，你可以找到志同道合的朋友，共同成长进步。让我们一起用代码改变世界！</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  


  </div>







<!-- End About -->









<section class="page-section" id="contact">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading text-uppercase">
          <p>Contact Us</p>
</h2>
        <h3 class="section-subheading text-muted">Lorem ipsum or call 123456789</h3>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-12">
        <form id="contactForm"
          action="https://formspree.io/your-email@example.com"
          novalidate="novalidate" method="POST">
          
          <div class="row">
            <div class="col-md-6">
              <div class="form-group">
                <input name="name" class="form-control" id="name" type="text"
                  placeholder="Name*"
                  required="required" data-validation-required-message="Please enter your name.">
                <p class="help-block text-danger"></p>
              </div>
              <div class="form-group">
                <input name="_replyto" class="form-control" id="email" type="email"
                  placeholder="Email*"
                  required="required" data-validation-required-message="Please enter your email address.">
                <p class="help-block text-danger"></p>
              </div>
              <div class="form-group">
                <input name="phone" class="form-control" id="phone" type="tel"
                  placeholder="Phone Number"
                  required="required" data-validation-required-message="Please enter your phone number.">
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="col-md-6">
              <div class="form-group">
                <textarea name="message" class="form-control" id="message"
                  placeholder="Message*"
                  required="required" data-validation-required-message="Please enter a message."></textarea>
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <input type="hidden" name="_subject" id="email-subject"
              value="Contact Form Submission">
            <div class="clearfix"></div>
            <div class="col-lg-12 text-center">
              <div id="success"></div>
              <button id="sendMessageButton" class="btn btn-primary btn-xl text-uppercase"
                type="submit">Send Message</button>
            </div>
            <input type="text" name="_gotcha" style="display:none">
            <input type="hidden" name="_next" value="#" />
          </div>
        </form>
      </div>
    </div>
  </div>
</section>

<!-- End Contact -->


	  <!-- Footer -->
<footer class="footer" id="footer" style="background-color: white">
  <div class="container">
    
    <div class="row align-items-center">
      <div class="col-md-4">
        <span class="copyright"
          >Copyright &copy; Your Awesome Website 2025</span
        >
      </div>
      <!-- Social Media -->
      <div class="col-md-4">
        <ul class="list-inline social-buttons">
          
          <li class="list-inline-item">
            
            <a href="https://twitter.com">
              <i class="fab fa-twitter"></i>
            </a>
            
          </li>
          
          <li class="list-inline-item">
            
            <a href="https://facebook.com">
              <i class="fab fa-facebook-f"></i>
            </a>
            
          </li>
          
          <li class="list-inline-item">
            
            <a href="https://linkedin.com">
              <i class="fab fa-linkedin-in"></i>
            </a>
            
          </li>
          
          <li class="list-inline-item">
            
            <a href="https://github.com/raviriley/agency-jekyll-theme">
              <i class="fab fa-github"></i>
            </a>
            
          </li>
          
          <li class="list-inline-item">
            
            <a href="https://instagram.com">
              <i class="fab fa-instagram"></i>
            </a>
            
          </li>
          
        </ul>
      </div>
      <!-- Legal -->
      <div class="col-md-4">
        <ul class="list-inline quicklinks">
          <li class="list-inline-item">
            <a href="legal"
              >Privacy Policy</a
            >
          </li>
        </ul>
      </div>
    </div>
    
  </div>
</footer>

<!-- End Footer -->


	  <!-- Bootstrap core JavaScript -->
	  <script src="assets/js/jquery.min.js"></script>
	  <script src="assets/js/bootstrap.bundle.min.js"></script>

	  <!-- Plugin JavaScript -->
	  <script src="assets/js/jquery.easing.min.js"></script>

	  <!-- Contact form JavaScript -->
	  <script src="assets/js/jqBootstrapValidation.js"></script>
	  <script src="assets/js/contact_me.js"></script>

	  <!-- Custom scripts for this template -->
	  <script src="assets/js/agency.min.js"></script>

  </body>

