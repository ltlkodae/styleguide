Google Style Guides - 한국어 번역
===================

모든 오픈소스 프로젝트는 각자의 style guide가 있다: 프로젝트에서 어떻게 코드를
작성하는가에 대한 규칙들. 모든 코드가 일관된 스타일로 작성됬을때, 수많은 코드를 
이해하기가 훨씬 쉬워진다.

"Style"은 많은 것을 포함한다. "변수 이름은 camelCase를 사용해라" 부터
"전역변수는 절대 사용하지 말아라", "예외는 절대 사용하지 말아라" 까지.
이 프로젝트는 우리사 사용하는 Google 코드의 style guidelines이다. 
만일 너가 Google의 프로젝트를 수정한다면, 이 페이지에서 프로젝트에 
적용되는 style guide를 볼수 있다.

[C++ Style Guide][cpp], [Objective-C Style Guide][objc], [Java Style
Guide][java], [Python Style Guide][py], [R Style Guide][r], [Shell Style
Guide][sh], [HTML/CSS Style Guide][htmlcss], [JavaScript Style Guide][js],
[AngularJS Style Guide][angular], [Common Lisp Style Guide][cl], and [Vimscript
Style Guide][vim] 를 볼수 있다. 또한 [cpplint][cpplint], style guide 정책을 
위한 tool, 그리고 [google-c-style.el][emacs], Google 스타일을 위한 Emacs 
설정파일도 공개되어 있다.

_현재 번역 완료된 문서는 
없으며, 
[Shell Style Guide][sh] 
번역이 진행중이다. - 프로젝트내 korean 디렉토리 확인_

만일 당신의 프로젝트에서 새로운 XML 문서 포맷을 만들고자 한다면, our [XML
Document Format Style Guide][xml] 가 도움이 될것이다. style 규칙 외에도,
디자인에 대한 조언과, XML 문서 형식, 요소와 특성에 대한 내용도 포함되어 있다.

이 style guide 는 CC-By 3.0 라이센스를 따르고 있으며, 당신의 것도 공유하기를
원한다. 자세한 내용은
[https://creativecommons.org/licenses/by/3.0/](https://creativecommons.org/licenses/by/3.0/)
을 참고해라

---

Every major open-source project has its own style guide: a set of conventions
(sometimes arbitrary) about how to write code for that project. It is much
easier to understand a large codebase when all the code in it is in a
consistent style.

“Style” covers a lot of ground, from “use camelCase for variable names” to
“never use global variables” to “never use exceptions.” This project holds the
style guidelines we use for Google code. If you are modifying a project that
originated at Google, you may be pointed to this page to see the style guides
that apply to that project.

Our [C++ Style Guide][cpp], [Objective-C Style Guide][objc], [Java Style
Guide][java], [Python Style Guide][py], [R Style Guide][r], [Shell Style
Guide][sh], [HTML/CSS Style Guide][htmlcss], [JavaScript Style Guide][js],
[AngularJS Style Guide][angular], [Common Lisp Style Guide][cl], and [Vimscript
Style Guide][vim] are now available. We have also released [cpplint][cpplint],
a tool to assist with style guide compliance, and [google-c-style.el][emacs],
an Emacs settings file for Google style.

If your project requires that you create a new XML document format, our [XML
Document Format Style Guide][xml] may be helpful. In addition to actual style
rules, it also contains advice on designing your own vs. adapting an existing
format, on XML instance document formatting, and on elements vs. attributes.

These style guides are licensed under the CC-By 3.0 License, which encourages
you to share these documents. See [https://creativecommons.org/licenses/by/3.0/](https://creativecommons.org/licenses/by/3.0/)
for more details.

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>

[cpp]: https://google.github.io/styleguide/cppguide.html
[objc]: https://google.github.io/styleguide/objcguide.xml
[java]: https://google.github.io/styleguide/javaguide.html
[py]: https://google.github.io/styleguide/pyguide.html
[r]: https://google.github.io/styleguide/Rguide.xml
[sh]: https://google.github.io/styleguide/shell.xml
[htmlcss]: https://google.github.io/styleguide/htmlcssguide.xml
[js]: https://google.github.io/styleguide/javascriptguide.xml
[angular]: https://google.github.io/styleguide/angularjs-google-style.html
[cl]: https://google.github.io/styleguide/lispguide.xml
[vim]: https://google.github.io/styleguide/vimscriptguide.xml
[cpplint]: https://github.com/google/styleguide/tree/gh-pages/cpplint
[emacs]: https://raw.githubusercontent.com/google/styleguide/gh-pages/google-c-style.el
[xml]: https://google.github.io/styleguide/xmlstyle.html
