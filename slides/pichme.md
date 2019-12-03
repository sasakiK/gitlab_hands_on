---
marp: true
theme: base
description: Gitlab Hands-on slide
paginate: true
footer: Git/Gitlab Hands-on
---

<!-- size: 4:3 -->

<style>
    @font-face
    {
        font-family: banana;
        src: url('./assets/bananaslip.otf')
    }
    section {
        background:#F5BF6A;
        color:#060000;
        font-family: 'banana';
        justify-content: flex-start;
    }
    h1{
        color:#060000;
    }
    p{
        color:#060000;
    }
    li {
        list-style-type: none;
    }
    li:before {
        content: '';
        width: 6px;
        height: 6px;
        display: inline-block;
        border-radius: 100%;
        background: #060000;
        position: relative;
        left: -15px;
        top: -5px;
    }
    table {
    padding: inherit;
    }
    th {
        background: #D5EBDC;
        color: #2A2B25;
        font-size: 18px;
    }
    td{
        color: #2A2B25;
        font-size: 14px;
    }
</style>

<style scoped>
    section {
        justify-content: center;
    }
    p{
        text-align: center;
        margin-top: 10%;
        font-size: 18px;
    }
</style>

# Git/Gitlab Hands-on

- 今日のゴール
- Gitとは
    - やってみる
- Gitlabとは
    - やってみる
- 1人でGit
- 2人でGitlab

2019.11.06

---

# Hands-onの目的

## その1

- アプリを作ったことがある状態にすること

---