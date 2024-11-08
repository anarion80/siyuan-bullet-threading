<p align="center">
<img alt="SiYuan" src="https://raw.githubusercontent.com/anarion80/siyuan-bullet-threading/refs/heads/main/icon.png">
<br>
<em>SiYuan Bullet Threading</em>
<br><br>
<a title="Releases" target="_blank" href="https://github.com/anarion80/siyuan-bullet-threading/releases"><img src="https://img.shields.io/github/v/release/anarion80/siyuan-bullet-threading?style=flat-square&color=9CF"></a>
<a title="Downloads" target="_blank" href="https://github.com/anarion80/siyuan-bullet-threading/releases"><img src="https://img.shields.io/github/downloads/anarion80/siyuan-bullet-threading/total.svg?style=flat-square&color=blueviolet"></a>
<br>
<a title="MIT" target="_blank" href="https://opensource.org/license/mit"><img src="https://img.shields.io/github/license/anarion80/siyuan-bullet-threading"></a>
<a title="Code Size" target="_blank" href="https://github.com/anarion80/siyuan-bullet-threading"><img src="https://img.shields.io/github/languages/code-size/anarion80/siyuan-bullet-threading.svg?style=flat-square&color=yellow"></a>
<a title="GitHub Pull Requests" target="_blank" href="https://github.com/anarion80/siyuan-bullet-threading/pulls"><img src="https://img.shields.io/github/issues-pr-closed/anarion80/siyuan-bullet-threading.svg?style=flat-square&color=FF9966"></a>
<br>
<a title="GitHub Commits" target="_blank" href="https://github.com/anarion80/siyuan-bullet-threading/commits/main"><img src="https://img.shields.io/github/commit-activity/m/anarion80/siyuan-bullet-threading.svg?style=flat-square"></a>
<a title="Last Commit" target="_blank" href="https://github.com/anarion80/siyuan-bullet-threading/commits/main"><img src="https://img.shields.io/github/last-commit/anarion80/siyuan-bullet-threading.svg?style=flat-square&color=FF9900"></a>
<br>
</p>

<p align="center">
<a href="README.md">English</a> | <a href="README_pl_PL.md">Polish</a>
</p>

## ✨ Opis wtyczki

Jest to wtyczka, która dodaje linie łączące punkty i podpunkty zagnieżdżonych list (nieuporządkowanych, uporządkowanych i list zadań).

Cała wtyczka jest wyodrębniona i przepakowana z doskonałego motywu [Rem-Craft](https://github.com/svchord/Rem-Craft) (nie chciałem używać całego motywu, tylko te linie łączące), więc wszystkie zasługi należą się [svchord](https://github.com/svchord).

Zmieniłem tylko lekko pozycje linii łączących ponieważ nie były dopasowane centralnei do kropki/liczby.

Wtyczka oryginalnie bazuje na wersji LogSeq: [https://github.com/pengx17/logseq-plugin-bullet-threading](https://github.com/pengx17/logseq-plugin-bullet-threading).

## ⌨ Użytkowanie

Wystarczy dodać zagnieżdżone punkty do listy i ustawić na nich kursor (lub przewinąć widok do nich). Wtyczka nie zawiera własnych stylów, więc linie między punktami będą odpowiednio białe/czarne w trybie ciemnym/jasnym. Powinny zmienić kolor na wartość `--text-brand`, gdy będzie ona dostępna w używanym temacie.

Jeśli `--text-brand` nie występuje w twoim temacie, możesz dodać następujący code snippet w ustawieniach SiYuan:

```css
:root {
    --text-brand: rgb(69, 130, 230);
}

:root.dark {
    --text-brand: rgb(97, 175, 239);
}
```

aby ustwić wymagane kolory.
