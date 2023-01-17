---
title: rsyncの sshオプションで blogを zip圧縮した ファイルを　ブログ用サーバーに転送した
date: 2023-01-17 06:41:11
tags:
---
# Used *rsync* to transfer blog HTML files to `www.yskz.xyz`.
なぜかrsyncでディレクトリごと転送すると`index.html`ファイルが全て空すなわちサイズ0になってしまう。
Failed to transfer all HTML files in *blog* folder; 'cause every HTML file size is zero.

やむなくblogディレクトリをアーカイブして一つのファイルにまとめて転送することで切り抜けた。
So, archived files into a zip format file.

Archive command is:
`zip -r blog.zip blog`

Extract command is:
`unzip blog.zip -d blog`
