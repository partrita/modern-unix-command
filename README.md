<h1 align="center">모던 Unix</h1>

## Table of Contents
- [bat](#bat)
- [eza](#eza)
- [lsd](#lsd)
- [delta](#delta)
- [dust](#dust)
- [duf](#duf)
- [broot](#broot)
- [fd](#fd)
- [ripgrep](#ripgrep)
- [fzf](#fzf)
- [mcfly](#mcfly)
- [choose](#choose)
- [jq](#jq)
- [sd](#sd)
- [cheat](#cheat)
- [tldr](#tldr)
- [bottom](#bottom)
- [glances](#glances)
- [gtop](#gtop)
- [hyperfine](#hyperfine)
- [gping](#gping)
- [procs](#procs)
- [httpie](#httpie)
- [curlie](#curlie)
- [xh](#xh)
- [zoxide](#zoxide)
- [doggo](#doggo)
- [lazygit](#lazygit)
- [navi](#navi)
- [zellij](#zellij)
- [starship](#starship)

<p align="center">
  <h1 align="center">
    <a href="https://github.com/sharkdp/bat"><code id="bat">bat</code></a>
  </h1>
  <p align="center">`cat` 복제 도구로, 구문 강조 및 Git 통합 기능을 제공합니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>bat README.md</code></pre>
  </p>
  <p align="center">
    <img src="https://camo.githubusercontent.com/a9789c5200bdb0a22602643d7bf85f0f424ddd4259e763abc865609010c5e228/68747470733a2f2f696d6775722e636f6d2f724773646e44652e706e67" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/eza-community/eza"><code id="eza">eza</code></a>
  </h1>
  <p align="center">`ls`를 대체하는 최신의 유지 관리되는 도구로, `exa`를 기반으로 합니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>eza -l --icons</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/eza-community/eza/main/docs/images/screenshots.png" width="700" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/Peltoche/lsd"><code id="lsd">lsd</code></a>
  </h1>
  <p align="center">차세대 파일 목록 명령어입니다. `ls`와 하위 호환됩니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>lsd -l</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/Peltoche/lsd/assets/screen_lsd.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/dandavison/delta"><code id="delta">delta</code></a>
  </h1>
  <p align="center">`git` 및 `diff` 출력을 위한 뷰어입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>git diff | delta</code></pre>
  </p>
  <p align="center">
    <img src="https://user-images.githubusercontent.com/52205/86275526-76792100-bba1-11ea-9e78-6be9baa80b29.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/bootandy/dust"><code id="dust">dust</code></a>
  </h1>
  <p align="center">rust로 작성된 `du`의 더 직관적인 버전입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>dust</code></pre>
  </p>
  <p align="center">
    <img src="https://user-images.githubusercontent.com/200613/90223722-e0c2e980-de0e-11ea-8c75-343273fed6f3.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/muesli/duf"><code id="duf">duf</code></a>
  </h1>
  <p align="center">더 나은 `df` 대안입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>duf</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/muesli/duf/master/duf.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/Canop/broot"><code id="broot">broot</code></a>
  </h1>
  <p align="center">디렉토리 `tree`를 보고 탐색하는 새로운 방법입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>broot</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/Canop/broot/master/website/docs/img/20200629-overview.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/sharkdp/fd"><code id="fd">fd</code></a>
  </h1>
  <p align="center">`find`를 대체하는 간단하고 빠르며 사용자 친화적인 도구입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>fd keyword</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/sharkdp/fd/master/doc/screencast.svg" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/BurntSushi/ripgrep"><code id="ripgrep">ripgrep</code></a>
  </h1>
  <p align="center">gitignore를 존중하는 매우 빠른 `grep` 대안입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>rg keyword</code></pre>
  </p>
  <p align="center">
    <img src="https://user-images.githubusercontent.com/200613/90223748-ecaeab80-de0e-11ea-9140-ac9219f5747c.gif" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/junegunn/fzf"><code id="fzf">fzf</code></a>
  </h1>
  <p align="center">범용 명령줄 퍼지 파인더입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>history | fzf</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/junegunn/i/master/fzf-preview.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/cantino/mcfly"><code id="mcfly">mcfly</code></a>
  </h1>
  <p align="center">셸 `history`를 빠르게 탐색합니다. Great Scott!</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>mcfly search keyword</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/cantino/mcfly/master/docs/screenshot.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/theryangeary/choose"><code id="choose">choose</code></a>
  </h1>
  <p align="center">`cut` 및 (때로는) `awk`를 대체하는 인간 친화적이고 빠른 도구입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>echo "a b c" | choose 1</code></pre>
  </p>
  <p align="center">
    <a href="https://asciinema.org/a/315932" target="_blank"><img src="https://asciinema.org/a/315932.svg" width="600" /></a>
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/stedolan/jq"><code id="jq">jq</code></a>
  </h1>
  <p align="center">
    JSON 데이터를 위한 `sed`입니다.
  </p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>echo '{"key": "value"}' | jq .key</code></pre>
  </p>
  <p align="center">
    <img src="https://blog.noenieto.com/media/gnome-shell-screenshot-VMABUZ.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/chmln/sd"><code id="sd">sd</code></a>
  </h1>
  <p align="center">직관적인 찾기 및 바꾸기 CLI (`sed` 대안)입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>echo "old text" | sd "old" "new"</code></pre>
    <pre><code>echo 'lots((([]))) of special chars' | sd -F '((([])))' ''</code></pre>
    <pre><code>echo 'lorem ipsum 23   ' | sd '\s+$' ''</code></pre>
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/cheat/cheat"><code id="cheat">cheat</code></a>
  </h1>
  <p align="center">명령줄에서 대화형 치트 시트를 만들고 봅니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>cheat tar</code></pre>
  </p>
  <p align="center">
    <img src="https://static.haydenjames.io/wp-content/uploads/2020/09/cheat-command-line-github-868x478.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/tldr-pages/tldr"><code id="tldr">tldr</code></a>
  </h1>
  <p align="center">실용적인 예제로 `man` 페이지를 단순화하려는 커뮤니티 노력입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>tldr tar</code></pre>
  </p>
  <p align="center">
    <img src="https://github.com/tldr-pages/tldr/raw/main/images/tldr-dark.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/ClementTsang/bottom"><code id="bottom">bottom</code></a>
  </h1>
  <p align="center">또 다른 크로스 플랫폼 그래픽 프로세스/시스템 모니터입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>btm</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/ClementTsang/bottom/master/assets/demo.gif" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/nicolargo/glances"><code id="glances">glances</code></a>
  </h1>
  <p align="center">시스템을 한눈에 파악합니다. GNU/Linux, BSD, Mac OS 및 Windows 운영 체제를 위한 `top`/`htop` 대안입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>glances</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/nicolargo/glances/develop/docs/_static/glances-summary.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/aksakalli/gtop"><code id="gtop">gtop</code></a>
  </h1>
  <p align="center">터미널용 시스템 모니터링 대시보드입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>gtop</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/aksakalli/gtop/master/img/demo.gif" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/sharkdp/hyperfine"><code id="hyperfine">hyperfine</code></a>
  </h1>
  <p align="center">명령줄 벤치마킹 도구입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>hyperfine 'sleep 0.1' 'sleep 0.2'</code></pre>
  </p>
  <p align="center">
    <img src="https://camo.githubusercontent.com/9bac9fc730637ebd007bdc51c6ec43d1e49b6f7ed92f00e087b71ec9c175fda6/68747470733a2f2f692e696d6775722e636f6d2f7a31394f5978452e676966" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/orf/gping"><code id="gping">gping</code></a>
  </h1>
  <p align="center">그래프가 있는 `ping`입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>gping google.com</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/orf/gping/master/images/readme-example.gif" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/dalance/procs"><code id="procs">procs</code></a>
  </h1>
  <p align="center">Rust로 작성된 `ps`의 최신 대체 도구입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>procs</code></pre>
  </p>
  <p align="center">
    <img src="https://user-images.githubusercontent.com/200613/90223676-c8eb6580-de0e-11ea-8e3e-fea30f173aab.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/httpie/httpie"><code id="httpie">httpie</code></a>
  </h1>
  <p align="center">API 시대를 위한 현대적이고 사용자 친화적인 명령줄 HTTP 클라이언트입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>http GET google.com</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/httpie/httpie/master/docs/httpie-animation.gif" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/rs/curlie"><code id="curlie">curlie</code></a>
  </h1>
  <p align="center">`curl`의 강력함과 `httpie`의 사용 편의성을 갖췄습니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>curlie google.com</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/rs/curlie/master/doc/get.png" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/ducaale/xh"><code id="xh">xh</code></a>
  </h1>
  <p align="center">HTTP 요청을 보내는 친숙하고 빠른 도구입니다. HTTPie의 뛰어난 디자인을 최대한 재현하면서 성능 향상에 중점을 두었습니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>xh GET google.com</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/ducaale/xh/master/assets/xh-demo.gif" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/ajeetdsouza/zoxide"><code id="zoxide">zoxide</code></a>
  </h1>
  <p align="center">`z`에서 영감을 받은 더 스마트한 `cd` 명령어입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>z foo</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/contrib/tutorial.webp" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/mr-karan/doggo"><code id="doggo">doggo</code></a>
  </h1>
  <p align="center">🐶 사람을 위한 명령줄 DNS 클라이언트입니다. `dig`의 강화 버전입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>doggo google.com</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/mr-karan/doggo/main/www/static/doggo.png" width="700" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/jesseduffield/lazygit"><code id="lazygit">lazygit</code></a>
  </h1>
  <p align="center">`git` 명령을 위한 간단한 터미널 UI입니다.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>lazygit</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/jesseduffield/lazygit/assets/staging.gif" width="700" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/denisidoro/navi"><code id="navi">navi</code></a>
  </h1>
  <p align="center">An interactive cheatsheet tool for the command-line.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>navi</code></pre>
  </p>
  <p align="center">
    [![asciicast](https://asciinema.org/a/406461.svg)](https://asciinema.org/a/406461)
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/zellij-org/zellij"><code id="zellij">zellij</code></a>
  </h1>
  <p align="center">A terminal workspace with batteries included.</p>
  <p align="center"><strong>예시:</strong></p>
  <p align="center">
    <pre><code>zellij</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/zellij-org/zellij/main/assets/demo.gif" width="600" />
  </p>
</p>

<p align="center">
  <h1 align="center">
    <a href="https://github.com/starship/starship"><code id="starship">starship</code></a>
  </h1>
  <p align="center">The minimal, blazing-fast, and infinitely customizable prompt for any shell!</p>
  <p align="center"><strong>예시 (추가 `~/.bashrc`):</strong></p>
  <p align="center">
    <pre><code>eval "$(starship init bash)"</code></pre>
  </p>
  <p align="center">
    <img src="https://raw.githubusercontent.com/starship/starship/master/media/demo.gif" width="600" />
  </p>
</p>
