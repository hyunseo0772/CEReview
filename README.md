# CEReview
Coding Everyday Review
- 생활 코딩 복습

index.html
- 생활 코딩에서 배웠던, 동영상 삽입, 채팅기능, 댓글 기능, 방문자 확인 기능을 사용하기 위한 메인 메뉴

video.html
- 생활 코딩에서 배웠던, 동영상 삽입 기능을 구현하기 위한 페이지
- youtube.com에서 호미들 '꽉 쥔 주먹속의 라이터' 뮤직비디오 주소를 복사했다.
<iframe width="560" height="315" src="https://www.youtube.com/embed/dvpysZxfDz0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

reply.html
- 생활 코딩에서 배웠던, 댓글 기능을 구현하기 위한 페이지
- https://disqus.com/ 사이트에서 아래 코드를 <body>에 추가하여 구현
<div id="disqus_thread"></div>
  <script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://web1-wfj7vl7jch.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

chat.html
- 생활 코딩에서 배웠던, 채팅 기능을 구현하기 위한 페이지
- https://dashboard.tawk.to/ 에서 Property URL에서 https://hyunseo0772.github.io/CEReview/chat.html을 적용하면 된다.

visit.html
- 생활 코딩에서 배웠던, 방문자 확인 기능을 구현하기 위한 페이지
- https://github.com/hyunseo0772/CEReview/visit.html 주소를 적용하여 실시간으로 방문자의 위치와 명수를 확인할 수 있다.
