---
layout: post
title: "The merits of the three-pane AI UX"
date: 2026-01-25
---

An AI UX pattern that was new to me, after using ChatGPT in the browser, was Cursor's three-pane layout. 

In this layout, I've got a file explorer – a list of folders that I can expand and collapse, each containing different text files; an editor in the centre of the screen where I can see and edit the contents of one file at a time; and finally on the right, my AI chat assistant. 

This layout really clicked me with. I tried to reflect on why, and there's a couple of reasons.

First, all the context that the AI chat has is clearly listed in the file explorer pane. This is a bit similar to the concept of uploading files or adding "knowledge" to a Custom GPT or Claude Project, but the files feel closer to hand in this three-pane layout than they do in a GPT or Project.

Secondly, the chat's output can be saved into new files. This completely blurs the lines between the "knowledge" that is  input by me into the project, and the outputs that the chat generates. This was the biggest initial mind-shift that drew me to this layout. Custom GPTs never hit the mark for me, because I immediately felt that I wanted to collaborate with the chat on creating or editing the context. And indeed, what I usually did was save files that the chat generated and then upload them to the context. But this amount of round-tripping between the chat UI and my filesystem was too much friction to make this a smooth or enjoyable experience.

Thirdly, having the file editor in the middle allows both me and the chat to be equal partners in the drafting of the text. In the browser ChatGPT experience, I was frustrated by having to always tell the chat to make small changes that I could more easily do myself – and even that was rarely accurate. In this three-pane layout, I have full control to edit what the chat writes. 

Today, I'm using this layout in Visual Studio Code, and it's possible to try out this experience with a free Github account, or you can get an API key from a model provider with a few dollar's worth of credits to try it out. 