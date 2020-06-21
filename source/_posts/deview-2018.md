---
title: Deview 2018 리뷰 (Day 1, Day2)
date: 2018-10-14 18:26:26
tags: deview
categories: blog
coverImage : deview.png
thumbnailImage: deview_front.png
---
회사 내에서도 대학시절 수강신청마냥 1분도 안되서 마감될 정도로 관심이 많았던 `DEVIEW 2018`. 다행히 클릭신공으로 운좋게 신청에 성공하였고 팀에서도 바쁜 시기였지만 감사하게도 보내주셔서 올해는 이틀 모두 다녀올수 있게 되었다.<!-- more --> 예전에는 `연차가 올라가면 DEVIEW행사는 참여 안하겠지~`라는 생각이 있었는데 그때는 단순 호기심에 참석을 하고 싶었다면 이번에는 `뭐라도 배워오자`라는 마음으로 신입 시절보다 조금더 성숙한 마음가짐과 자세를 가지고 참석을 하게 되었다.
> 다시 생각해보면 호기심만으로 세션들을 듣고 부스에서 나눠주는 굿즈를 조금이라도 더 받아와야지 하고 생각했던 신입시절의 생각이 틀린건 아니였지만, 말 그대로 `기술행사`이니만큼 가급적이면 세션에서 발표하는 내용을 내것으로 만들고 실무에서 또는 다른곳에서 활용할수는 없을까 하는 생각을 갖는게 보다 성장하려는 개발자로서의 자세가 아닐까 생각이 든다. (라고 멋드러지게 말하지만 세션내용의 절반이라도 이해하면 다행이겠지...)

### # 행사 시작 그리고 키노트
10초만에 마감되었다는 소리가 있을정도로 올해도 여전히 관심이 많았던 `DEVIEW 2018`. 코엑스에 도착하고 등록을 한뒤 이곳저곳 부스들을 구경하기 바빴다. 이번에는 지난번과 달리 거의 네이버 서비스가 60~70%를 자리잡고 있었고(파파고, 지도, 클로바, 글로벌 광고 등등) 일반 기업에서는 얼마 오지 않았다.(내 기억으로 5~6개?) 개인적으로 여러 다양한 회사들이 함께하는 기술행사가 되었으면 하는 바램이 있었지만 회사를 선정하는데, 그리고 기타 사정들이 있을꺼라는 아쉬움을 뒤로하고 CTO님이 발표하시는 키노트를 들으러 메인강의장에 들어갔다. (자칫... 이것도 네이버 독과점(?) 이러면 할말이 없는데...ㅠㅠ)
{% image center keynote.png 송창현 네이버 CTO님의 keynote %}
작년에는 거의 `로봇잔치`로 느껴졌는데 올해는 그 기술들의 융합(?)잔치 로 받아들여졌다. `Ambient Intelligence` 를 강조하시며 `기술의 진정한 가치는 기술이 생활속으로 사라졌을 때 나온다`라는 명언같은 말씀도 해주셨다. 
- 연결 : 사물, 상황, 위치인식, 이해
- 발견 : 적시에 답, 추천, 액션제공

그리고 그와 관련된 네이버 서비스를 공개 하셨는데, 네이버 지도 Map API를 무제한/무료로 사용할수 있게 된다고 한다. (박수 유도하심 ㅎㅎ) 또한 이번에 가장 크게 바뀌는 네이버 모바일 홈 페이지인 `그린닷`, 지도 기술들의 종합 플랫폼인 `xDM Platform`(측위, 지도, 내비), 그리고 자율주행과 로봇에 대해 연구결과 그리고 앞으로의 방향성에 대해 정리해주셨다. 집에 돌아와서 검색좀 하다보니 `테크수다`에서 벌써(?) 영상을 하나 올린게 있어 공유해본다.
<iframe width="560" height="315" src="https://www.youtube.com/embed/q2TM8KNnF14?rel=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
키노트를 다 듣고 작년에는 그런가보다 하고 별생각이 안들었는데 올해는 저런 기술들이 서비스 레벨까지 가는데 이렇다할 허들없이 사용자들에게 보여질수만 있다면 개발자로서 보다 더 큰 자부심을 가지고 기술개발에 정진할텐데... 하는 씁슬한 생각을 해보게 되었다. (물론 이런 부분들도 다 사정이 있을꺼라 생각이 들지만 안타까운건 감출수가 없을것 같다.)

이틀에 걸쳐 이런저런 다양한 세션들을 들을수 있어 좋았는데 몇몇 세션들은 기본지식이 없어 (AI, 머신러닝 등...ㅠ) 이해하기 힘들었다. 내년엔 이해할수 있도록 준비를 해서 오자며 `또`다짐을 하고... 그나마 조금이라도 이해할수 있었던 세션들 몇개만 정리해본다.

### # React Native: 웹 개발자가 한 달 만에 앱 출시하기
{% image center session_1.png React Native: 웹 개발자가 한 달 만에 앱 출시하기 %}
지난팀에서 아주 잠깐 React를 경험해보긴 했지만 거의 hello world 수준이였기 때문에 이 세션 역시 이해가 잘 되지 못했다. 하지만 필자처럼 이해를 잘 못하는 사람도 발표자가 전달하려는 목적이 무엇인지 알수 있을 정도로 전체적인 흐름은 조금이나마 이해를 할수 있었고 특히 개발하면서 좋았던 것이나 경험담을 알려주며 `삽질공유`를 해주는게 듣기 좋았다. React Native 는 빠른개발을 할수있고 코드공유가 쉬우며 개선이 쉽다는 장점이 있다고 한다. 또한 단기간에 크로스 플랫폼을 만들어야 할때 사용한다고 하니 나중에 참고해봐도 좋을듯 싶다.
- 발표자료
<iframe src="//www.slideshare.net/slideshow/embed_code/key/1UGMk1XHgSFIbL" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/deview/121react-native" title="[121]React Native: 웹 개발자가 한 달 만에 앱 출시하기" target="_blank">[121]React Native: 웹 개발자가 한 달 만에 앱 출시하기</a> </strong> from <strong><a href="https://www.slideshare.net/deview" target="_blank">NAVER D2</a></strong> </div>

### # LINE x NAVER 개발 보안 취약점 이야기
{% image center session_2.png LINE x NAVER 개발 보안 취약점 이야기 %}
`버그바운티`라는 신기한(?)프로그램에 대한 소개와 운영에 대한 내용을 발표해 주셨다. 가끔 사내에서도 `버그를 잡으면 포상을 드려요` 라는 글이 올라왔었는데 그때마다 손안데고 코풀려나 하는 비뚤어진(?)생각을 갖곤 했었다. 하지만 듣고보니 해커를 고용하는 가장 좋은 방법이면서도 회사의 보안을 지키는 가장 좋은 방법이라고 한다. 또한 잘 알려진 왠만한 기업들은 버그바운티 프로그램을 운영하고 있다고 한다. 비뚤어진 생각을 다시 고쳐 생각해보면, 해커에게는 취약점을 찾으며 해커 본연의 업무를 더욱더 발전시킬수 있고, 회사로써는 수만가지의 취약점을 관리하는 별도의 팀을 운영하는 비용보다 이러한 `버그바운티`라는 프로그램을 운영하면 선택과 집중을 하며 보다 효율적일것 같다는 생각이 들었다. 그러면서 어떠한 내용들로 보상을 해줬는가에 대해 소개를 해줬는데 가장 접하기 쉬운 XSS 공격이나 서버설정 미스로 인한 정보노출 등 아주 다양한 사례를 공유해 주셨다.
- 발표자료
<iframe src="//www.slideshare.net/slideshow/embed_code/key/MlweW8QkuAIhsg" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/deview/113linexnaver" title="[113]LINExNAVER 개발 보안 취약점 이야기" target="_blank">[113]LINExNAVER 개발 보안 취약점 이야기</a> </strong> from <strong><a href="https://www.slideshare.net/deview" target="_blank">NAVER D2</a></strong> </div>

### # 쿠팡 서비스 Cloud Migration을 통해 배운 것들
{% image center session_3.png 쿠팡 서비스 Cloud Migration을 통해 배운 것들 %}
사내에서도 발표가 있었는데 그때 제대로 못들어서 다시 듣게 되었다. 지난 2년동안 서비스를 클라우드로의 이전을 하면서 마주쳤던 문제들과 해결책, 그리고 클라우드의 마이크로서비스가 만나면서 마주친 새로운 문제들과 정리했던 생각들에 대해 공유하는 발표였다.
- 클라우드 이전원칙 : 확장성 확보하기 위함, 무중단 이전, 고객에게 만족도에 영향이 없어야 함
- 공통배포 파이프라인 유지, 만든사람이 운영하는 문화, 장애관리 문화

특히 `안정상태 찾기`라는 제목으로 서비스의 건강도를 측정하는 대시보드 형태의 페이지를 만들었다는 부분에서 내가 하고있는 서비스에서도 API Status 페이지처럼 서비스 전반에 대한 건강도(?)를 대시보드 형태로 충분히 만들수 있지 않을까 하는 생각을 해보았다.
- 발표자료
<iframe src="//www.slideshare.net/slideshow/embed_code/key/2KoOkDt1dbN9vl" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/deview/115-119061611" title="[115]쿠팡 서비스 클라우드 마이그레이션 통해 배운것들" target="_blank">[115]쿠팡 서비스 클라우드 마이그레이션 통해 배운것들</a> </strong> from <strong><a href="https://www.slideshare.net/deview" target="_blank">NAVER D2</a></strong> </div>

### # Druid로 쉽고 빠르게 빅데이터 분석하기
{% image center session_4.png Druid로 쉽고 빠르게 빅데이터 분석하기 %}
여태 참석한 DEVIEW 세션들 중에 시작전에 줄이 가장 길었던 세션(행사장 전체 반바퀴를 줄서야 했던 ;;) 그만큼 사람들도 빅데이터 분석에 대해 관심이 많이 있다는걸 증명하였고 나역시 Day1, Day2 전 세션들 중에 이 세션이 가장 기대가 되었다. Druid는 분석용도로 만든 플랫폼이고 아파치 인큐베이터에 들어가 있을정도로 각광받고 있는 플랫폼 이라고 한다. 일반적으로 빅데이터를 분석하기 위해서는 Druid와 Elasticsearch, Apache kudu 가 비교대상이 되는데 발표자분은 각 플랫폼을 아주 다양한 각도에서 비교 분석하며 현 상황에서 가장 적합한 플랫폼을 찾기위한 노력한 부분을 보여주셨다. 필자는 기존에 Elastic Stack을 백지부터 홀로 터득한 경험이 있어 무슨차이가 있는지 궁금했는데 가장 큰 다른점은 join과 group by가 된다는 장점이 있다고 한다. (join기능은 자체 제공하지는 않지만 spark와 연동해서 해결했다고 한다.)
또한 가장 관심갖고 봤던 비쥬얼라이징툴에 대해 소개해주셨는데 Imply UI소개를 듣고 감탄사가 절로 나왔지만 유료... 그라파나는 플러그인을 통한 다양한 그래프를 쉽게 표현이 가능하다고 하였고 Superset 은 표현할수있는 그래프가 가장 많고 권한관리도 입맛에 맞게 가능하다고 한다. 다만 너무 많아서 복잡할수도 있다고 ... Metabase는 어플리케이션 방식이고 깔끔한 UI를 제공하지만 세부적인 설정은 불가능 하다는 단점이 있다고 한다.
솔루션 선택을 할때 마냥 좋다고 사용하는것이 아니라 실제로 다양한 관점에서의 테스트를 해보고 서비스에 적절한 솔루션을 선택하는 좋은 발표를 들을수 있어서 너무 좋았다.
- 발표자료
<iframe src="//www.slideshare.net/slideshow/embed_code/key/7l1PlNxFsuExZ" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/deview/215-druid-119186559" title="[215] Druid로 쉽고 빠르게 데이터 분석하기" target="_blank">[215] Druid로 쉽고 빠르게 데이터 분석하기</a> </strong> from <strong><a href="https://www.slideshare.net/deview" target="_blank">NAVER D2</a></strong> </div>

### # 마치며
{% image center deview_last.png 나도 언젠간 스피커가 될수 있겠지...? %}
이번 Deview에서는 Facebook에서 알게된 POPit 저자분을 실제로 만나뵙기도 했고 지금은 S사에 계시는 우연히 만나게된 반가운 예전팀 형, 그리고 군 장교시절 필자의 소대원이 AI 스타트업 소속으로 부스를 운영을 하며 서비스 소개를 하고 있는 모습도 보고... 참 다양한 이벤트들이 많았던 행사였다. 사실 올해 Deview 발표자를 모집할때 `주니어 개발자가 회사밖에서 성장하는 방법` 같은 내용으로 발표를 해볼까도 생각했지만 지금생각해보면 좀더 준비를 철저히 그리고 깊게 해야겠다고 느꼈다. 
그리고 내가 하고있는 업무 즉, 서비스 운영/개발은 아무리 바쁘고 힘들어도 기본으로 해야하고 회사를 벗어나 신기술 또는 기존기술의 고도화 방법을 찾아서 공부하고 내것으로 만들어 나가야 하는건 예전이나 지금이나 변함이 없다는걸 다시한번 느낄수 있었던 좋은 행사였다고 생각한다. 이번에도 뒤통수 세게 맞고 간다...