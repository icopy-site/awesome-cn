<div class="github-widget" data-repo="git-tips/tips"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## git-tips
 &gt;集合git-tips，您要添加提示吗？  检查 [contributing.md](https://github.com/git-tips/tips/blob/master/./contributing.md)

[English](http://git.io/git-tips) | [中文](https://github.com/521xueweihan/git-tips) | [Русский](https://github.com/Imangazaliev/git-tips) | [한국어](https://github.com/mingrammer/git-tips) | [Tiếng Việt](https://github.com/hprobotic/git-tips) | [日本語](https://github.com/isotai/git-tips) | [नेपाली](https://github.com/amarduwal/git-tips) | [Polski](https://github.com/mbiesiad/tips)

### __Narzędzia:__

* [git-tip](https://www.npmjs.com/package/git-tip)  -便捷的CLI界面，可最佳使用这些技巧.  （[Tutaj jest kontener Docker](https://github.com/djoudi5/docker-git-tip))

PS：所有这些命令均在git版本2.7.4（Apple Git-66）上进行了测试.

<!-- @doxie.inject start toc -->
<!-- Don’t remove or change the comment above – that can break automatic updates. -->
* [Edytuj [local/global] git config](#edytuj-local-global-git-config)

<!-- Don’t remove or change the comment below – that can break automatic updates. More info at <http://npm.im/doxie.inject>. -->
<!-- @doxie.inject end toc -->


<!-- @doxie.inject start -->
<!-- Don’t remove or change the comment above – that can break automatic updates. -->
## Codziennie Git w około dwudziestu poleceniach
```sh
git每天帮助
```

## Pokaż przydatne przewodniki dla Git
```sh
git help -g
```

## Wyszukaj zmianę według zawartości
```sh
git log -S&#39; <a term in the source>&#39;</a>
```

## Pokaż zmiany w czasie dla określonego pliku
```sh
git log -p <file_name>
```

## Usuń wrażliwe dane z historii po push
```sh
 git filter-branch --force --index-filter&#39;git rm --cached --ignore-unmatch <path-to-your-file>  &#39;--prune-empty --tag-name-filter cat---all &amp;&amp; git push origin --force --all
```

## Synchronizuj ze zdalnym, zastępuj lokalne zmiany
```sh
git fetch origin &amp;&amp; git reset --hard origin / master &amp;&amp; git clean -f -d
```

## Lista wszystkich plików do commita
```sh
git ls-tree --name-only -r <commit-ish>
```

## Git zresetuj pierwszy commit
```sh
git update-ref -d头
```

## Reset: zachowaj niezatwierdzone zmiany lokalne
```sh
git reset-保持<commit>
```

## Wyświetl wszystkie skonfliktowane pliki
```sh
git diff-仅名称--diff-filter = U
```

## Lista wszystkich plików zmienionych w commitcie
```sh
git diff-tree --no-commit-id --name-only -r <commit-ish>
```

## Zmienione ale niezaktualizowane zmiany od ostatniego zatwierdzenia
```sh
git差异
```

## Porównanie zmian z poczekalni z ostatnią zmianą
```sh
git diff-缓存
```


__Alternatywnie:__
```sh
git diff --staged
```

## Pokaż wszystkie zmiany w śledzonych plikach.
```sh
git diff头
```

## Lista wszystkich gałęzi, które są już zmergowane do mastera
```sh
git branch-合并的主
```

## Szybko przełącz na poprzednią gałąź
```sh
git checkout-
```


__Alternatywnie:__
```sh
git checkout @ {-1}
```

## Usuń gałęzie które zostały już połączone z master
```sh
 git branch-合并的主|  grep -v&#39;^ \ *&#39;|  xargs -n 1 git分支-d
```


__Alternatywnie:__
```sh
git branch --merged master | grep -v '^\*\|  master' | xargs -n 1 git branch -d # will not delete master if master is not checked out
```

## Wymień wszystkie gałęzie i ich wyższe poziomy, a także ostatnie zatwierdzenie na gałęzi
```sh
git分支-vv
```

## Śledź odgałęzienie
```sh
git branch -u来源/ mybranch
```

## Usuń lokalną gałąź
```sh
git分支-d <local_branchname>
```

## Usuń zdalną gałąź
```sh
git push origin-删除<remote_branchname>
```


__Alternatywnie:__
```sh
git push来源： <remote_branchname>
```


```sh
git分支-dr <remote/branch>
```

## Usuń lokalny tag
```sh
git标签-d <tag-name>
```

## Usuń zdalny tag
```sh
git push origin：参考/标签/ <tag-name>
```

## Cofnij zmiany lokalne z ostatnią zawartością w head
```sh
git checkout- <file_name>
```

## Cofnij: Cofnij commita, tworząc nowego commita
```sh
去还原<commit-ish>
```

## Reset: Odrzuć commity, zalecane dla prywatnej gałęzi
```sh
git重置<commit-ish>
```

## Zmień kolejność poprzedniej wiadomości commita
```sh
git commit -v-修改
```

## Zobacz historię zatwierdzeń tylko dla bieżącej gałęzi
```sh
git cherry -v主控
```

## Zmień autora.
```sh
 git commit --amend --author =&#39;作者姓名 <email@address.com>  &#39;
```

## Resetuj autora po zmianie autora w global config.
```sh
git commit --amend --reset-author --no-edit
```

## Zmiana zdalnego adresu URL
```sh
git remote set-url的起源<URL>
```

## Uzyskaj listę wszystkich zdalnych referencji
```sh
git远程
```


__Alternatywnie:__
```sh
git远程显示
```

## Uzyskaj listę wszystkich lokalnych i zdalnych gałęzi
```sh
git分支-a
```

## Uzyskaj tylko zdalne gałęzie
```sh
git分支-r
```

## Śledź części zmienionego pliku zamiast całego pliku
```sh
git添加-p
```

## Uzyskaj ukończenie git bash
```sh
 curl -L http://git.io/vfhol&gt;〜/ .git-completion.bash &amp;&amp; echo&#39;[-f〜/ .git-completion.bash] &amp;&amp;.  〜/ .git-completion.bash&#39;&gt;&gt;〜/ .bashrc
```

## Co zmieniło się od dwóch tygodni?
```sh
git log --no-merges --raw --since =&#39;2周前&#39;
```


__Alternatywnie:__
```sh
git whatchanged --since =&#39;2周前&#39;
```

## Zobacz wszystkie zatwierdzenia dokonane od czasu forkowania z mastera
```sh
git log --no-merges --stat --reverse master ..
```

## Wybierz zatwierdzenia między gałęziami za pomocą cherry-pick
```sh
 git checkout <branch-name>  &amp;&amp; git cherry-pick <commit-ish>
```

## Znajdź gałęzie zawierające commit-hash
```sh
git branch -a-包含<commit-ish>
```


__Alternatywnie:__
```sh
git branch-包含<commit-ish>
```

## Aliasy Gita
```sh
git config-全局别名<handle><command> 
git config --global alias.st状态
```

## Zapisywanie bieżącego stanu śledzonych plików bez zatwierdzania
```sh
git stash
```


__Alternatywnie:__
```sh
git stash保存
```

## Zapisywanie aktualnego stanu zmian unstaged do śledzonych plików
```sh
git stash -k
```


__Alternatywnie:__
```sh
git stash --keep-index
```


```sh
git stash save --keep-index
```

## Zapisywanie bieżącego stanu, w tym nieśledzonych plików
```sh
去藏-u
```


__Alternatywnie:__
```sh
git stash save -u
```


```sh
git stash save --include-untracked
```

## Zapisywanie aktualnego stanu z komunikatem
```sh
git stash保存<message>
```

## Zapisywanie bieżącego stanu wszystkich plików (ignorowanych, nieśledzonych i śledzonych)
```sh
git stash -a
```


__Alternatywnie:__
```sh
git stash --all
```


```sh
git stash save --all
```

## Pokaż listę wszystkich zapisanych stashes
```sh
git存储列表
```

## Zastosuj dowolony stash bez usuwania z listy stashed
```sh
git stash适用<stash@{n}>
```

## Zastosuj ostatni stan stashed i usuń go z listy stashed
```sh
git stash pop
```


__Alternatywnie:__
```sh
git stash应用stash @ {0} &amp;&amp; git stash drop存放stash @ {0}
```

## Usuń wszystkie przechowywane stashes
```sh
git隐藏
```


__Alternatywnie:__
```sh
git隐藏<stash@{n}>
```

## Weź pojedynczy plik z pliku stash
```sh
 git checkout <stash@{n}>  - <file_path>
```


__Alternatywnie:__
```sh
git checkout stash @ {0}- <file_path>
```

## Pokaż wszystkie śledzone pliki
```sh
git ls文件-t
```

## Pokaż wszystkie nieśledzone pliki
```sh
git ls-files-其他
```

## Pokaż wszystkie zignorowane pliki
```sh
git ls-files --others -i --exclude-standard
```

## Utwórz nowe drzewo robocze z repozytorium (git 2.5)
```sh
git工作树添加-b <branch-name><path><start-point>
```

## Utwórz nowe drzewo robocze ze stanu HEAD
```sh
 git worktree添加--detach <path>  头
```

## Przestań śledzić pliki bez usuwania
```sh
git rm-缓存<file_path>
```


__Alternatywnie:__
```sh
git rm-缓存-r <directory_path>
```

## Przed usunięciem nieśledzonych plików / katalogu, wykonaj próbę, aby uzyskać listę tych plików / katalogów
```sh
git clean -n
```

## Wymuś usunięcie nieśledzonych plików
```sh
git clean -f
```

## Wymuś usunięcie nieśledzonego katalogu
```sh
git clean -f -d
```

## Zaktualizuj wszystkie submoduły
```sh
git子模块foreach git pull
```


__Alternatywnie:__
```sh
git子模块更新--init --recursive
```


```sh
git子模块更新-远程
```

## Pokaż wszystkie zatwierdzenia w bieżącym branchu, które mają zostać zmergowane do mastera
```sh
git cherry -v主控
```


__Alternatywnie:__
```sh
git cherry -v主控<branch-to-be-merged>
```

## Zmień nazwę brancha
```sh
git分支-m <new-branch-name>
```


__Alternatywnie:__
```sh
 git branch -m [ <old-branch-name>  ] <new-branch-name>
```

## Rebase 'feature' do 'master' i merguj to do master 
```sh
git rebase master功能&amp;&amp; git checkout master &amp;&amp; git merge-
```

## Zarchiwizuj branch `master`
```sh
git archive master --format = zip --output = master.zip
```

## Zmodyfikuj poprzednie zatwierdzenie bez modyfikowania komunikatu zatwierdzenia
```sh
git add --all &amp;&amp; git commit --amend --no-edit
```

## Czyści odniesienia do zdalnych gałęzi, które zostały usunięte na zdalnym.
```sh
git fetch -p
```


__Alternatywnie:__
```sh
git remote prune起源
```

## Pobierz skrót zatwierdzenia z początkowej wersji.
```sh
  git rev-list --reverse HEAD |复制代码  头-1
```


__Alternatywnie:__
```sh
git rev-list --max-parents = 0头
```


```sh
 git log --pretty = oneline |  尾巴-1 |  切-c 1-40
```


```sh
 git log --pretty = oneline --reverse |  头-1 |  切-c 1-40
```

## Wizualizuj drzewo wersji.
```sh
git log --pretty = oneline --graph --decorate --all
```


__Alternatywnie:__
```sh
gitk-全部
```


```sh
 git log --graph --pretty =格式：&#39;％C（auto）％h |  ％s |  ％an |  ％ar％d&#39;
```

## Wizualizuj drzewo, w tym zatwierdzenia, do których odwołuje się tylko dziennik rejestrów
```sh
git log --graph --decorate --oneline $（git rev-list --walk-reflogs --all）
```

## Wdrażanie podfolderu śledzonego przez git do gh-pages
```sh
git subtree push --prefix subfolder_name原始gh-pages
```

## Dodanie projektu do repozytorium za pomocą poddrzewa
```sh
 git子树添加--prefix = <directory_name>  / <project_name>  --squash git@github.com： <username>  / <project_name>  .git master
```

## Pobierz najnowsze zmiany w repozytorium dla połączonego projektu za pomocą poddrzewa
```sh
 git subtree pull --prefix = <directory_name>  / <project_name>  --squash git@github.com： <username>  / <project_name>  .git master
```

## Wyeksportuj gałąź z historią do pliku.
```sh
git bundle创建<file><branch-name>
```

## Importuj z pakietu
```sh
 git clone repo.bundle <repo-dir>  -b <branch-name>
```

## Uzyskaj nazwę bieżącego brancha.
```sh
git rev-parse --abbrev-ref头
```

## Zignoruj jeden plik przy zatwierdzaniu (np. Changelog).
```sh
 git update-index-假定不变的变更日志;  git commit -a;  git update-index-无假设不变的变更日志
```

## Stashuj zmiany przed rebasing'iem
```sh
git rebase --autostash
```

## Pobierz pull request według identyfikatora do lokalnego brancha
```sh
 git fetch origin pull / <id>  /头： <branch-name>
```


__Alternatywnie:__
```sh
 git pull origin pull / <id>  /头： <branch-name>
```

## Pokaż najnowszy tag w bieżącym branchu.
```sh
git describe --tags --abbrev = 0
```

## Pokaż inline word diff.
```sh
git diff --word-diff
```

## Pokaż zmiany używając narzędzi common diff.
```sh
 git difftool [-t <tool>  ] <commit1><commit2><path>
```

## Nie rozważaj zmian w śledzonym pliku.
```sh
git update-index-假定不变<file_name>
```

## Cofnij assume-unchanged.
```sh
git update-index-无假设不变<file_name>
```

## Wyczyść pliki z `.gitignore`.
```sh
git clean -X -f
```

## Przywróć usunięty plik.
```sh
 git checkout <deleting_commit>  ^- <file_path>
```

## Przywróć plik do określonego commit-hash
```sh
 git checkout <commit-ish>  - <file_path>
```

## Zawsze rebase zamiast merge na pull.
```sh
git config --global pull.rebase是
```


__Alternatywnie:__
```sh
#git < 1.7.9
git config --global branch.autosetuprebase总是
```

## Wyświetl wszystkie aliasy i konfiguracje.
```sh
git config --list
```

## Uwzględnij wielkość liter w git.
```sh
git config --global core.ignorecase否
```

## Dodaj niestandardowe edytory.
```sh
git config --global core.editor&#39;$ EDITOR&#39;
```

## Automatyczne poprawianie literówek.
```sh
git config --global help.autocorrect 1
```

## Sprawdź, czy zmiana była częścią wydania.
```sh
git name-rev-仅名称<SHA-1>
```

## Dry run. (dowolne polecenie obsługujące flagę dry-run powinno zrobić.)
```sh
git clean -fd --dry-run
```

## Oznacza twoje zatwierdzenie jako poprawkę poprzedniego zatwierdzenia.
```sh
git commit --fixup <SHA-1>
```

## Squash fixup commits normal commits.
```sh
git rebase -i-自动压扁
```

## Pomiń staging area podczas commitowania.
```sh
git commit-仅<file_path>
```

## Interaktywny staging.
```sh
git添加-i
```

## Lista ignorowanych plików.
```sh
git check-ignore *
```

## Status zignorowanych plików.
```sh
git status-忽略
```

## Commity w Branch1 które nie są w Branch2
```sh
git log Branch1 ^ Branch2
```

## Wyświetl listę n ostatnich commitów
```sh
git日志- <n>
```


__Alternatywnie:__
```sh
git log -n <n>
```

## Ponownie użyj recorded resolution, record and reuse previous conflicts resolutions.
```sh
git config --global rerere.enabled 1
```

## Otwórz wszystkie skonfliktowane pliki w edytorze.
```sh
 git diff-仅名称|  uniq |  xargs $ EDITOR
```

## Policz wypakowaną liczbę obiektów i ich zużycie dysku.
```sh
git count-objects-可读
```

## Wyczyść wszystkie nieosiągalne obiekty z bazy danych obiektów.
```sh
git gc --prune = now --aggressive
```

## Natychmiast przeglądaj działające repozytorium w gitweb.
```sh
 git instaweb [--local] [--httpd = <httpd>  ] [--port = <port>  ] [--browser = <browser>  ]
```

## Wyświetl podpisy GPG w dzienniku zatwierdzeń
```sh
git log --show-signature
```

## Usuń wpis w globalnej konfiguracji.
```sh
git config --global --unset <entry-name>
```

## Checkout nowego brancha bez historii
```sh
git checkout-孤立<branch_name>
```

## Wyodrębnij plik z innej gałęzi.
```sh
 git show <branch_name>  ： <file_name>
```

## Wymień tylko root i merge commits.
```sh
git log --first-parent
```

## Zmień poprzednie dwa zatwierdzenia za pomocą interaktywnego rebase.
```sh
git rebase-交互式HEAD〜2
```

## Wymień wszystkie gałęzie, których praca jest w toku (WIP)
```sh
git checkout master &amp;&amp; git分支-不合并
```

## Znajdź nieczyste korzystając z wyszukiwania binarnego
```sh
git bisect start                    # Search start 
git bisect bad                      # Set point to bad commit 
git bisect good v2.6.13-rc2         # Set point to good commit|tag 
git bisect bad                      # Say current state is bad 
git bisect good                     # Say current state is good 
git bisect reset                    # Finish search 

```

## Bypass pre-commit and commit-msg githooks
```sh
git commit --no-verify
```

## Lista zatwierdzeń i zmian w określonym pliku (nawet poprzez zmianę nazwy)
```sh
git log-关注-p- <file_path>
```

## Klonuj pojedynczy branch
```sh
 git clone -b <branch-name>  --single-branch https://github.com/user/repo.git
```

## Utwórz i zmień nowy branch
```sh
git checkout -b <branch-name>
```


__Alternatywnie:__
```sh
 git分支 <branch-name>  &amp;&amp; git结帐 <branch-name>
```

## Ignoruj tryb zmiany plików na commitach
```sh
git config core.fileMode错误
```

## Wyłącz git colored terminal output
```sh
git config --global color.ui false
```

## Określone ustawienia kolorów
```sh
git config --global <specific command e.g branch, diff><true, false or always>
```

## Pokaż wszystkie lokalne branche uporządkowane według ostatnich commitów
```sh
git for-each-ref --sort = -committerdate --format =&#39;％（refname：short）&#39;refs / heads /
```

## Znajdź wiersze pasujące do wzorca (wyrażenia regularnego lub ciągu) w śledzonych plikach
```sh
git grep --heading --line-number&#39;foo bar&#39;
```

## Sklonuj płytką kopię repozytorium
```sh
git clone https://github.com/user/repo.git --depth 1
```

## Wyszukaj Commit log we wszystkich branchach dla podanego tekstu
```sh
 git log --all --grep =&#39; <given-text>  &#39;
```

## Uzyskaj pierwszy commit w branchu (z master)
```sh
 git log --oneline主站 <branch-name>  |  尾-1
```


__Alternatywnie:__
```sh
 git log --reverse master .. <branch-name>  |  头-6
```

## Unstaging Staged file
```sh
git reset HEAD <file-name>
```

## Wymuś wypchnięcie do zdalnego repozytorium
```sh
git push -f <remote-name><branch-name>
```

## Dodawanie nazwy zdalnej
```sh
git远程添加<remote-nickname><remote-url>
```

## Wyświetl listę wszystkich aktualnie skonfigurowanych zdalnych
```sh
git remote -v
```

## Pokaż autora, czas i ostatnią wersję dokonaną w każdej linii danego pliku
```sh
吉特怪<file-name>
```

## Grupuj commity według autorów i tytułów
```sh
git shortlog
```

## Wymuś pusha, ale nadal upewnij się, że nie nadpisujesz pracy innych
```sh
git push-强制租赁<remote-name><branch-name>
```

## Pokaż, ile wierszy ma współautor
```sh
 git log --author =&#39;_ Your_Name_Here_&#39;--pretty = tformat：--numstat |  gawk&#39;{添加+ = <!-- @doxie.inject start -->  ;  潜艇+ = <!-- @doxie.inject end -->  ;  loc + = <!-- @doxie.inject start -->  -- <!-- @doxie.inject end -->  } END {printf“添加了行：％s已删除行：％s总行：％s
“，添加，订阅，位置}&#39;-
```


__Alternatywnie:__
```sh
 git log --author =&#39;_ Your_Name_Here_&#39;--pretty = tformat：--numstat |  awk&#39;{添加+ = <!-- @doxie.inject start -->  ;  潜艇+ = <!-- @doxie.inject end -->  ;  loc + = <!-- @doxie.inject start -->  -- <!-- @doxie.inject end -->  } END {printf“添加了行：％s，已删除的行：％s，总行：％s
", add, subs, loc }' - # on Mac OSX
```

## Cofnij: Cofnięcie całego merge
```sh
git revert -m 1 <commit-ish>
```

## Liczba commitów w branchu
```sh
git rev-list --count <branch-name>
```

## Alias: git undo - cofnij
```sh
 git config --global alias.undo&#39;！f（）{git reset --hard $（git rev-parse --abbrev-ref HEAD）@ {$ {1-1}};  };  F&#39;
```

## Dodaj notatkę obiektu
```sh
git notes add -m&#39;上一次提交的注释....
```

## Pokaż wszystkie git-notes
```sh
git log --show-notes =&#39;*&#39;
```

## Zastosuj commit z innego repozytorium
```sh
 git --git-dir = <source-dir>  /.git format-patch -k -1 --stdout <SHA1>  |  去-3 -k
```

## Specific fetch reference
```sh
git fetch origin master:refs/remotes/origin/mymaster
```

## Znajdź wspólnego przodka dwóch gałęzi
```sh
git merge-base <branch-name><other-branch-name>
```

## Wyświetl unpushed git commits
```sh
git log --branches --not --remotes
```


__Alternatywnie:__
```sh
git log @ {u} ..
```


```sh
吉特樱桃-v
```

## Dodaj wszystko, ale bez zmiany białych znaków
```sh
 git diff --ignore-all-space |  git apply --cached
```

## Edytuj [local/global] git config
```sh
git config [--global] --edit
```

## blame on certain range
```sh
 git怪-L <start>  ， <end>
```

## Pokaż zmienną logiczną Git.
```sh
git var -l | <variable>
```

## Preformatted patch file.
```sh
git format-patch -M上游..主题
```

## Uzyskaj nazwę repozytorium.
```sh
git rev-parse --show-toplevel
```

## logi między zakresem dat
```sh
git log --since =&#39;FEB 1 2017&#39;--until =&#39;FEB 14 2017&#39;
```

## Wyklucz autora z logów
```sh
git log --perl-regexp --author =&#39;^（（?!排除作者正则表达式）.*）

```

## Generuj podsumowanie oczekujących zmian
```sh
git request-pull v1.0 https：//git.ko.xz/project master：for-linus
```

## Lista referencji w zdalnym repozytorium
```sh
git ls-远程git：//git.kernel.org/pub/scm/git/git.git
```

## Utwórz kopię zapasową nieśledzonych plików.
```sh
 git ls文件--others -i --exclude-standard |  xargs zip untracked.zip
```

## Wyświetl wszystkie aliasy git
```sh
 混帐配置-l |  grep的其他|  的sed的/ ^其他\ .// G&#39;
```


__Alternatywnie:__
```sh
 git config -l |  grep别名|  切-d&#39;.  -f 2
```

## Pokaż git status short
```sh
git status --short-分支
```

## Sprawdź commit sprzed dnia
```sh
git checkout master @ {昨天}
```

## Popchnij nowy branch lokalny do zdalnego repozytorium i śledź
```sh
git push -u起源<branch_name>
```

## Zmień branch base
```sh
git rebase --onto <new_base><old_base>
```

## Użyj SSH zamiast HTTPs dla remotes
```sh
git config --global url.&#39;git@github.com：&#39;.insteadOf&#39;https://github.com/&#39;
```

## Zaktualizuj submoduł do najnowszego commita
```sh
光盘<path-to-submodule>
git pull起源<branch>
光盘<root-of-your-main-project>
git添加<path-to-submodule>
git commit -m“子模块已更新”
```

## Zapobiegaj automatycznemu zastępowaniu LF przez CRLF
```sh
git config --global core.autocrlf否
```

<!-- Don’t remove or change the comment below – that can break automatic updates. More info at <http://npm.im/doxie.inject>. -->
<!-- @doxie.inject end -->
