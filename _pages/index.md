---
permalink: /
layout: index
title: Kyle Klus
---
<div class="content" style="display:flex; flex-direction:column; ">
    <div class="image-cropper" style="width: 200px; height: 200px; align-self: center;">
        <a href="https://github.com/MajorEnkidu" style="margin: 0">
            <img src="https://github.com/MajorEnkidu.png" alt="Profile Picture" class="rounded"/>
        </a>
    </div>
    <br>
    <div style="align-self: center;">
        <button class="portfolio-button" onclick="location.href = '/Kyles-Cookbook.html'">My Cookbook</button>
        <button class="portfolio-button" onclick="location.href = 'https://github.com/MajorEnkidu?tab=repositories'">Portfolio</button>
        <button class="portfolio-button" onclick="location.href = 'mailto:kyle.klus.work@pm.me'">Contact</button>
    </div>
    <hr>
    <br><br>
    <p style="align-self: center;">Hi, I am Kyle Klus, a computer science student </p>
    <p style="align-self: center;">with a love for creating things for myself and/or for others.</p>
    <br>
    <p style="align-self: center;">Feel free to roam around and have a look at my current projects and</p>
    <p style="align-self: center;">maybe you'll find something interesting or even cook the recipes in my</p>
    <p style="align-self: center;">cookbook yourself.</p>
    <br>
    <p style="align-self: center;">- Kyle Klus</p>
    <br><br>
    <style>
        .image-cropper {
            position: relative;
            overflow: hidden;
            border-radius: 50%;
            box-shadow: var(--shadow);
            border: 1px solid var(--main-accent-dark);
            transition: all 200ms ease-out;
        }
        .image-cropper:hover {
            transform: scale(1.02);
            transition: all 200ms ease-in;
        }
        img.rounded{
            display: inline;
            margin: 0 auto;
            height: 100%;
            width: auto;
        }
        .portfolio-button{
            width: max-content;
            color: var(--text-normal);
            background-color: var(--bg-darker);
            border: none;
            border-radius: var(--radius-big);
            padding: 12px;
            margin:1.2rem 0;
            align-self: center;
            box-shadow: var(--button-shadow);
            transition: all 200ms ease-out;
        }
        .portfolio-button:hover{
            background-color: var(--bg-dark);
            transform: translateY(-1px);
            transition: all 200ms ease-in;
            cursor: pointer;
        }
    </style>
</div>
