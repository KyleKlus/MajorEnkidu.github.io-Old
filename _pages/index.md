---
permalink: /
layout: index
title: MajorEnkidu
---
<div class="content" style="display:flex; flex-direction:column; align-items:center;">
    <div class="image-cropper" style="width: 200px; height: 200px;">
        <a href="https://github.com/MajorEnkidu" style="margin: 0">
            <img src="https://github.com/MajorEnkidu.png" alt="Profile Picture" class="rounded"/>
        </a>
    </div>
    <br>
    <div style="display: flex;flex-direction: row;flex-wrap: wrap;align-content: center;justify-content: center;align-items: center;margin-bottom: 1rem;">
        <button class="portfolio-button" onclick="location.href = '/Kyles-Cookbook.html'">My Cookbook</button>
        <button class="portfolio-button" onclick="location.href = 'https://github.com/MajorEnkidu?tab=repositories'">GitHub</button>
        <button class="portfolio-button" onclick="location.href = 'mailto:kyle.klus.work@pm.me'">Contact</button>
    </div>
    <div>
        <script type='text/javascript' src='https://storage.ko-fi.com/cdn/widget/Widget_2.js'></script>
        <script type='text/javascript'>
            kofiwidget2.init('Support Me on Ko-fi', '#bd3131', 'W7W1D5JTZ');
            kofiwidget2.draw();
        </script>
    </div>
    <br>
    <br><br>
    <p style="text-align:center">Hi, I am Kyle Klus, a computer science student </p>
    <p style="text-align:center">with a love for creating things, for myself and/or for others.</p>
    <br>
    <p style="text-align:center">Feel free to roam around and have a look at my current projects and</p>
    <p style="text-align:center">maybe you'll find something interesting or even cook the recipes in my</p>
    <p style="text-align:center">cookbook yourself.</p>
    <br>
    <p style="text-align:center">- Kyle Klus</p>
    <br><br>
    <style>
        .image-cropper {
            display: inline;
            height: 100%;
            width: 100%;
            position: relative;
            overflow: hidden;
            border-radius: 50%;
            box-shadow: var(--shadow);
            border: 1px solid var(--main-accent-dark);
            transition: transform 200ms ease-out;
        }
        .image-cropper:hover {
            transform: scale(1.02);
            transition: transform 200ms ease-in;
        }
        img.rounded{
            display: inline;
            height: 100%;
            width: 100%;
        }
        .portfolio-button{
            width: max-content;
            color: var(--text-normal);
            background-color: var(--bg-darker);
            border: none;
            border-radius: var(--radius-big);
            padding: 12px;
            margin: 0.5rem;
            align-self: center;
            box-shadow: var(--button-shadow);
            transition: all 200ms ease-out;
        }
        .btn-container{
            border-radius: 8px;
            box-shadow: var(--button-shadow);
            transition: all 200ms ease-out;
        }
        .portfolio-button:hover,
        .btn-container:hover {
            background-color: var(--bg-dark);
            transform: translateY(-1px);
            transition: all 200ms ease-in;
            cursor: pointer;
        }
    </style>
</div>
