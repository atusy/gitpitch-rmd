GitPitch ❤ Rmd
================

### Rmd を GitPitch してみる．

GitPitch は GitHub などに上げた md ファイルをスライド化してくれる． 実態は reveal.js．

-----

### Rmd を GitPitch するとなにがいいの？

  - git 管理するファイルを削減できそう
      - reveal.js スライドに出力した html
      - `self_contained: false` な場合の `js` ファイルなど
  - 出先で文言だけ修正したい時には GitHub 上で md ファイル弄っとけばいい

-----

### 作図

``` r
hist(rnorm(1e3), breaks = "Scott")
```

![](PITCHME_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->
