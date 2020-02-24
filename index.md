---
layout: home
---

<div class="base">
  <div class="row justify-content-left splash-console">

    <h2>Alexander Clarke</h2>

    <div class="console-item">
      <div class="console-command">
        <span class="console-name">site</span>:~$ cat description.md
      </div>
      <div class="console-output">
        Junior programmer, working towards being full-stack.
        Coffee fiend.
        <br>
        Thanks for popping by! :v)
      </div>
    </div>

    <div class="console-item">
      <div class="console-command">
        <span class="console-name">site</span>:~$ cat social-media.md
      </div>
      <div class="console-output">
         {%- include social.html -%}
      </div>
    </div>

    <div class="console-item">
      <div class="console-command">
        <span class="console-name">site</span>:~$ cat projects.md
      </div>
      <div class="console-output">
        {% include projects-list.html %}
      </div>
    </div>

    <div class="console-item">
      <div class="console-command">
        <span class="console-name">site</span>:~$ cat volunteering.md
      </div>
      <div class="console-output">
        {% include volunteering-list.html %}
      </div>
    </div>
  </div>
</div>

