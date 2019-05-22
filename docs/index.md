<link rel="stylesheet" href="_static/css/main.css">

## 构建文档的中文镜像
### 输入英文文档url立即构建镜像
<div class="s130">
    <div class="form">
        <div class="inner-form">
            <div class="input-field first-wrap">
                <div class="svg-wrapper">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24px" height="24px">
                        <path style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal" d="M 5 3 C 3.9069372 3 3 3.9069372 3 5 L 3 19 C 3 20.093063 3.9069372 21 5 21 L 19 21 C 20.093063 21 21 20.093063 21 19 L 21 12 L 19 12 L 19 19 L 5 19 L 5 5 L 12 5 L 12 3 L 5 3 z M 14 3 L 14 5 L 17.585938 5 L 8.2929688 14.292969 L 9.7070312 15.707031 L 19 6.4140625 L 19 10 L 21 10 L 21 3 L 14 3 z" font-weight="400" font-family="sans-serif" white-space="normal" overflow="visible"/>
                    </svg>
                </div>
                <input id="url" type="text" placeholder="英文文档URL"/>
            </div>
            <div class="input-field second-wrap">
                <button class="btn-search" type="button" onclick='go()' >构建</button>
            </div>
        </div>
        <span class="error" id="status"></span>
    </div>
</div>
<script src="https://cdn.bootcss.com/jquery/3.3.1/jquery.min.js"></script>
<script type="text/javascript">
    function go() {
        var url = $("#url").val();
        if (!url.startsWith("http")) {
            url = "http://" + url;
        }
        var targetUrl = "https://"+"icopy.site/" + url;
        try {
            var urlAddress = new URL(url);
            window.location = targetUrl;
        } catch (e) {
            $("#status").text("URL 不合法");
        }
    }
</script>

### 地址栏URL前加icopy.site/

 <img src="/_static/img/barImg.jpg" style="width:100%;border-radius:10px;box-shadow: 0 8px 17px 0 rgba(0,0,0,.2),0 6px 20px 0 rgba(0,0,0,.19)">

[![Build Status](https://travis-ci.org/icopy-site/icopy-site.github.io.svg?branch=develop)](https://travis-ci.org/icopy-site/icopy-site.github.io)

## 提供的服务
* *本站提供英文文档的中文镜像服务,镜像网站每周定期更新*
* *整理汇总各类文档资源*

## 服务限制

!!! warning "为防止滥用,只支持静态文档网站的镜像"
    网站域名或者网页路径中需要包含以下关键词:doc,guide,tutorial,manual,dev关键词
    
!!! warning "对于不满足以上条件的文档可以添加白名单"
    需要添加白名单,请在github提issue
        
!!! warning "镜像网站每周更新"
    内容最多比源站落后7天,网站定时检查,清理缓存超过7天的网页        

## 内容优化

!!! info "替换源站无法访问的静态资源"

!!! info "代码片段不会翻译"

!!! info "翻译内容鼠标滑过会显示英文原文"

 **本文档采用 [mkdocs](https://github.com/mkdocs/mkdocs) 构建**



