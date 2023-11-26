<!DOCTYPE html>
<html>
<head>
    <title>MEO アンケート</title>
    <meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="VkomOJ0Jtv+yw++Un5hlGoh8oZTyA7nonw3Ut5eJwY17ssD7aJ+ZYhwyh78oIlaCTCN2tSRutqIuMZuuTIS+uQ==" />
    

    <link rel="stylesheet" media="all" href="/assets/application-c9dffae9194ba7a751f2ea2fe5d4ed7a3a1d4ce35c1b2fe594eeb9f5d1fcba94.css" />
    <meta charset="utf-8" />
<link rel="apple-touch-icon" sizes="76x76" href="/static/img/apple-icon.png">
<link rel="icon" type="image/png" href="/static/img/MEODashboard_favicon.ico">
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
<meta content='width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0, shrink-to-fit=no' name='viewport' />
<!--     Fonts and icons     -->
<link rel="stylesheet" href="/static/css/font-awesome.min.css" />

<!-- CSS Files -->

<link href="/static/css/bootstrap.min.css" rel="stylesheet" />
<link href="/static/css/light-bootstrap-dashboard.css?v=2.0.1" rel="stylesheet" />
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
<link href="/static/css/bootstrap-daterangepicker.min.css" rel="stylesheet" />
<link href="/static/css/cropper.min.css" rel="stylesheet" />
<!--   JQuery   -->
<script src="/static/js/core/jquery.3.6.0.min.js" type="text/javascript"></script>
<script src="/static/js/plugins/jquery-ui.min.js" type="text/javascript"></script>
<link href="/static/css/jquery-ui.min.css" rel="stylesheet" />
<!-- DEMO用 -->
<link href="/static/css/select2.min.css" rel="stylesheet" />
<script src="/static/js/plugins/select2.min.js"></script>
<link href="/static/atlaport/atlaport.css" rel="stylesheet" />
<script src="/static/atlaport/atlaport.js"></script>
<script src="/static/js/plugins/highcharts.js" type="text/javascript"></script>
<script src="/static/js/plugins/jquery.twbsPagination.js" type="text/javascript"></script>
<script src="/static/js/plugins/jmap.min.js" type="text/javascript"></script>
<script charset="utf-8" src="https://static.line-scdn.net/liff/edge/2/sdk.js"></script>

    <style type="text/css" media="screen">
      #app_fs_store { margin-bottom: 50px; }
      #app_fs_store header {
        background-color: #1da1f2;
        color: #fff;
        padding: 1rem;
        text-align: center;
        display: block;
      }
      #app_fs_store .content {
        padding: 1rem;
      }
      #app_fs_store .text-center {
        text-align: center !important;
      }
      #app_fs_store .font_size_xs {
        font-size: 80%;
      }
      #app_fs_store ol, #app_fs_store ul, #app_fs_store dl {
        margin-top: 0;
        margin-bottom: 1rem;
      }
      #app_fs_store .questionForm dt {
        margin-bottom: 1rem;
      }
      #app_fs_store b, #app_fs_store strong {
        font-weight: bolder;
      }
      #app_fs_store dd {
        margin-bottom: 0.5rem;
        margin-left: 0;
      }
      #app_fs_store .questionForm dd ul {
        padding: 0;
        list-style: none;
      }
      #app_fs_store .questionForm dd ul li {
        background: #efefef;
        margin-bottom: 1rem;
      }
      #app_fs_store .questionForm dd ul li label {
        margin: 0;
        padding: 0.5rem 0.6rem;
        display: block;
      }
      #app_fs_store input[type=radio], #app_fs_store input[type=checkbox] {
        box-sizing: border-box;
        padding: 0;
      }
      #app_fs_store .btn-next {
        background: #1da1f2;
        color: #fff;
        width: 70%;
        max-width: 400px;
        cursor: pointer;
        display: inline-block;
        font-weight: 400;
        text-align: center;
        vertical-align: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        user-select: none;
        border: 1px solid transparent;
        padding: 0.375rem 0.75rem;
        font-size: 1rem;
        line-height: 1.5;
        border-radius: 0.25rem;
        transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
      }
      #app_fs_store .btn-next.btn-next-gray {
        background-color: #888;
      }
      #app_fs_store .endpage {
        padding: 3rem 0;
      }
      #app_fs_store .font_size_s {
        font-size: 90%;
      }
      #app_fs_store .feedback-box {
        border: 2px solid #e3e3e3;
        padding: 1.25em;
      }
     .btn-next:hover, .btn-next:focus, .btn-next:active {
        background-color: #198caa !important;
        border-color: #198caa !important;
      }
      .btn-next:focus {
        outline: 0;
      }
      #app_fs_store .review-text {
        width: 100%;
        height: 90px;
        padding: 15px;
      }
    </style>
</head>
<body>
      <div id="app_fs_store">
        <main>
          <div id="fs_store">
            <div>
              <div>
                <header>粉もんスタンドおしんアンケート</header>
                <div class="content calendar-content">
                  <div id="question_title" class="text-center">アンケートのご協力をお願いいたします</div>
                  <p class="font_size_xs text-center">(所要時間1分)</p>
                  <dl class="questionForm">
                    <dt>
                      <strong>Q.ご来店ありがとうございました。本日は満足していただけましたでしょうか</strong>
                    </dt>
                    <dd>
                      <ul>
                          <li>
                              <label><input name="radio-follow" type="radio" value="150581">&nbsp;非常に満足</label>
                          </li>
                          <li>
                              <label><input name="radio-follow" type="radio" value="150582">&nbsp;満足</label>
                          </li>
                          <li>
                              <label><input name="radio-follow" type="radio" value="150583">&nbsp;どちらでもない</label>
                          </li>
                          <li>
                              <label><input name="radio-follow" type="radio" value="150584">&nbsp;不満</label>
                          </li>
                          <li>
                              <label><input name="radio-follow" type="radio" value="150585">&nbsp;非常に不満</label>
                          </li>
                      </ul>
                    </dd>
                  </dl>
                </div>
              </div>
              <div><p id="msgError" style="color: red; text-align: center;display: none;">アンケートを選択してください</p></div>
              <div class="text-center">
                <button type="button" class="btn-next" id="submitQuestion1">次 へ</button>
              </div>
            </div>
          </div>
        </main>
      </div>

    <script type="text/javascript">
      $(document).on('click', '#submitQuestion1', function() {
        var inputValue = $('input[name=radio-follow]:checked').val();
        if (inputValue  == undefined){
          $('#msgError').show();
        } else {
          $('#msgError').hide();

          $.ajax({
            url: '/submit_question',
            type:'POST',
            dataType:'script',
            data: {
              questionnaire_detail_select_id: inputValue,
              questionnaire_detail_id: 31124,
              questionnaire_id: 27068,
              count_question: 0,
              qa_id: null,
              input_type: "0"
            },
            success: function(){
              return true;
            }
          });
        }
      });

      $(document).on('click', '#submitQuestion2', function() {
        var text = $('.review-text').val();
        if (text.length > 400) {
          $('#msgError1').show();
        } else {
          $('#msgError1').hide();
          $.ajax({
            url: '/submit_question',
            type:'POST',
            dataType:'script',
            data: {
              review_text: text,
              questionnaire_detail_id: 31124,
              questionnaire_id: 27068,
              count_question: 0,
              qa_id: null,
              input_type: "0"
            },
            success: function(){
              return true;
            }
          });
        }
      });
    </script>

</body>
</html>
