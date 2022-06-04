---
permalink: /
layout: default
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
        <button class="portfolio-button" onclick="location.href = 'https://github.com/MajorEnkidu?tab=repositories'">Portfolio</button>
        <button class="portfolio-button" onclick="location.href = 'mailto:kyle.klus.work@pm.me'">Contact</button>
    </div>
    <hr>
    <br><br>
    <p>This is the Website of Kyle Klus.</p>
    <p>Feel free to roam around and cook any of the recipes you find, for yourself.</p>
    <br>
    <p>- Kyle Klus</p>
    <br><br>
    <style>
        .image-cropper {
            position: relative;
            overflow: hidden;
            border-radius: 50%;
            box-shadow: var(--shadow);
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
