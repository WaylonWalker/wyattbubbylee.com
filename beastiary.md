---
article_html: '<h2 id="bee">Bee</h2>

  <p><img alt="" src="/bee.png" />\</p>

  <p>## zombe</p>

  <p><img alt="" src="/zombe.png" /><div class=''prevnext''></p>

  <div class="codehilite"><pre><span></span><code><span class="nt">&lt;style</span><span
  class="w"> </span><span class="na">type=</span><span class="s">&#39;text/css&#39;</span><span
  class="nt">&gt;</span>


  :root<span class="w"> </span>{

  <span class="w">  </span>--prevnext-color-text:<span class="w"> </span>#eefbfe;

  <span class="w">  </span>--prevnext-color-angle:<span class="w"> </span>#e1bd00c9;

  <span class="w">  </span>--prevnext-subtitle-brightness:<span class="w"> </span>3;

  }

  [data-theme=&quot;light&quot;]<span class="w"> </span>{

  <span class="w">  </span>--prevnext-color-text:<span class="w"> </span>#1f2022;

  <span class="w">  </span>--prevnext-color-angle:<span class="w"> </span>#ffeb00;

  <span class="w">  </span>--prevnext-subtitle-brightness:<span class="w"> </span>3;

  }

  [data-theme=&quot;dark&quot;]<span class="w"> </span>{

  <span class="w">  </span>--prevnext-color-text:<span class="w"> </span>#eefbfe;

  <span class="w">  </span>--prevnext-color-angle:<span class="w"> </span>#e1bd00c9;

  <span class="w">  </span>--prevnext-subtitle-brightness:<span class="w"> </span>3;

  }

  .prevnext<span class="w"> </span>{

  <span class="w">  </span>display:<span class="w"> </span>flex;

  <span class="w">  </span>flex-direction:<span class="w"> </span>row;

  <span class="w">  </span>justify-content:<span class="w"> </span>space-around;

  <span class="w">  </span>align-items:<span class="w"> </span>flex-start;

  }

  .prevnext<span class="w"> </span>a<span class="w"> </span>{

  <span class="w">  </span>display:<span class="w"> </span>flex;

  <span class="w">  </span>align-items:<span class="w"> </span>center;

  <span class="w">  </span>width:<span class="w"> </span>100%;

  <span class="w">  </span>text-decoration:<span class="w"> </span>none;

  }

  a.next<span class="w"> </span>{

  <span class="w">  </span>justify-content:<span class="w"> </span>flex-end;

  }

  .prevnext<span class="w"> </span>a:hover<span class="w"> </span>{

  <span class="w">  </span>background:<span class="w"> </span>#00000006;

  }

  .prevnext-subtitle<span class="w"> </span>{

  <span class="w">  </span>color:<span class="w"> </span>var(--prevnext-color-text);

  <span class="w">  </span>filter:<span class="w"> </span>brightness(var(--prevnext-subtitle-brightness));

  <span class="w">  </span>font-size:<span class="w"> </span>.8rem;

  }

  .prevnext-title<span class="w"> </span>{

  <span class="w">  </span>color:<span class="w"> </span>var(--prevnext-color-text);

  <span class="w">  </span>font-size:<span class="w"> </span>1rem;

  }

  .prevnext-text<span class="w"> </span>{

  <span class="w">  </span>max-width:<span class="w"> </span>30vw;

  }

  <span class="nt">&lt;/style&gt;</span>


  <span class="nt">&lt;a</span><span class="w"> </span><span class="na">class=</span><span
  class="s">&#39;prev&#39;</span><span class="w"> </span><span class="na">href=</span><span
  class="s">&#39;/pygame-with-chatgpt&#39;</span><span class="nt">&gt;</span>



  <span class="w">    </span><span class="nt">&lt;svg</span><span class="w"> </span><span
  class="na">width=</span><span class="s">&quot;50px&quot;</span><span class="w">
  </span><span class="na">height=</span><span class="s">&quot;50px&quot;</span><span
  class="w"> </span><span class="na">viewbox=</span><span class="s">&quot;0 0 24 24&quot;</span><span
  class="w"> </span><span class="na">fill=</span><span class="s">&quot;none&quot;</span><span
  class="w"> </span><span class="na">xmlns=</span><span class="s">&quot;http://www.w3.org/2000/svg&quot;</span><span
  class="nt">&gt;</span>

  <span class="w">        </span><span class="nt">&lt;path</span><span class="w">
  </span><span class="na">d=</span><span class="s">&quot;M13.5 8.25L9.75 12L13.5 15.75&quot;</span><span
  class="w"> </span><span class="na">stroke=</span><span class="s">&quot;var(--prevnext-color-angle)&quot;</span><span
  class="w"> </span><span class="na">stroke-width=</span><span class="s">&quot;1.5&quot;</span><span
  class="w"> </span><span class="na">stroke-linecap=</span><span class="s">&quot;round&quot;</span><span
  class="w"> </span><span class="na">stroke-linejoin=</span><span class="s">&quot;round&quot;</span><span
  class="nt">&gt;</span><span class="w"> </span><span class="nt">&lt;/path&gt;</span>

  <span class="w">    </span><span class="nt">&lt;/svg&gt;</span>

  <span class="w">    </span><span class="nt">&lt;div</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-text&#39;</span><span class="nt">&gt;</span>

  <span class="w">        </span><span class="nt">&lt;p</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-subtitle&#39;</span><span
  class="nt">&gt;</span>prev<span class="nt">&lt;/p&gt;</span>

  <span class="w">        </span><span class="nt">&lt;p</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-title&#39;</span><span class="nt">&gt;</span>Pygame<span
  class="w"> </span>with<span class="w"> </span>chatgpt<span class="nt">&lt;/p&gt;</span>

  <span class="w">    </span><span class="nt">&lt;/div&gt;</span>

  <span class="nt">&lt;/a&gt;</span>


  <span class="nt">&lt;a</span><span class="w"> </span><span class="na">class=</span><span
  class="s">&#39;next&#39;</span><span class="w"> </span><span class="na">href=</span><span
  class="s">&#39;/&#39;</span><span class="nt">&gt;</span>


  <span class="w">    </span><span class="nt">&lt;div</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-text&#39;</span><span class="nt">&gt;</span>

  <span class="w">        </span><span class="nt">&lt;p</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-subtitle&#39;</span><span
  class="nt">&gt;</span>next<span class="nt">&lt;/p&gt;</span>

  <span class="w">        </span><span class="nt">&lt;p</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-title&#39;</span><span class="nt">&gt;</span>Wyatt&#39;s<span
  class="w"> </span>Minecraft<span class="w"> </span>Documentary<span class="nt">&lt;/p&gt;</span>

  <span class="w">    </span><span class="nt">&lt;/div&gt;</span>

  <span class="w">    </span><span class="nt">&lt;svg</span><span class="w"> </span><span
  class="na">width=</span><span class="s">&quot;50px&quot;</span><span class="w">
  </span><span class="na">height=</span><span class="s">&quot;50px&quot;</span><span
  class="w"> </span><span class="na">viewbox=</span><span class="s">&quot;0 0 24 24&quot;</span><span
  class="w"> </span><span class="na">fill=</span><span class="s">&quot;none&quot;</span><span
  class="w"> </span><span class="na">xmlns=</span><span class="s">&quot;http://www.w3.org/2000/svg&quot;</span><span
  class="nt">&gt;</span>

  <span class="w">        </span><span class="nt">&lt;path</span><span class="w">
  </span><span class="na">d=</span><span class="s">&quot;M10.5 15.75L14.25 12L10.5
  8.25&quot;</span><span class="w"> </span><span class="na">stroke=</span><span class="s">&quot;var(--prevnext-color-angle)&quot;</span><span
  class="w"> </span><span class="na">stroke-width=</span><span class="s">&quot;1.5&quot;</span><span
  class="w"> </span><span class="na">stroke-linecap=</span><span class="s">&quot;round&quot;</span><span
  class="w"> </span><span class="na">stroke-linejoin=</span><span class="s">&quot;round&quot;</span><span
  class="nt">&gt;&lt;/path&gt;</span>

  <span class="w">    </span><span class="nt">&lt;/svg&gt;</span>

  <span class="nt">&lt;/a&gt;</span>

  </code></pre></div>


  </div>'
cover: ''
date: 2022-12-07
datetime: 2022-12-07 00:00:00+00:00
description: ''
edit_link: https://github.com/edit/main/pages/beastiary.md
html: '<h2 id="bee">Bee</h2>

  <p><img alt="" src="/bee.png" />\</p>

  <p>## zombe</p>

  <p><img alt="" src="/zombe.png" /><div class=''prevnext''></p>

  <div class="codehilite"><pre><span></span><code><span class="nt">&lt;style</span><span
  class="w"> </span><span class="na">type=</span><span class="s">&#39;text/css&#39;</span><span
  class="nt">&gt;</span>


  :root<span class="w"> </span>{

  <span class="w">  </span>--prevnext-color-text:<span class="w"> </span>#eefbfe;

  <span class="w">  </span>--prevnext-color-angle:<span class="w"> </span>#e1bd00c9;

  <span class="w">  </span>--prevnext-subtitle-brightness:<span class="w"> </span>3;

  }

  [data-theme=&quot;light&quot;]<span class="w"> </span>{

  <span class="w">  </span>--prevnext-color-text:<span class="w"> </span>#1f2022;

  <span class="w">  </span>--prevnext-color-angle:<span class="w"> </span>#ffeb00;

  <span class="w">  </span>--prevnext-subtitle-brightness:<span class="w"> </span>3;

  }

  [data-theme=&quot;dark&quot;]<span class="w"> </span>{

  <span class="w">  </span>--prevnext-color-text:<span class="w"> </span>#eefbfe;

  <span class="w">  </span>--prevnext-color-angle:<span class="w"> </span>#e1bd00c9;

  <span class="w">  </span>--prevnext-subtitle-brightness:<span class="w"> </span>3;

  }

  .prevnext<span class="w"> </span>{

  <span class="w">  </span>display:<span class="w"> </span>flex;

  <span class="w">  </span>flex-direction:<span class="w"> </span>row;

  <span class="w">  </span>justify-content:<span class="w"> </span>space-around;

  <span class="w">  </span>align-items:<span class="w"> </span>flex-start;

  }

  .prevnext<span class="w"> </span>a<span class="w"> </span>{

  <span class="w">  </span>display:<span class="w"> </span>flex;

  <span class="w">  </span>align-items:<span class="w"> </span>center;

  <span class="w">  </span>width:<span class="w"> </span>100%;

  <span class="w">  </span>text-decoration:<span class="w"> </span>none;

  }

  a.next<span class="w"> </span>{

  <span class="w">  </span>justify-content:<span class="w"> </span>flex-end;

  }

  .prevnext<span class="w"> </span>a:hover<span class="w"> </span>{

  <span class="w">  </span>background:<span class="w"> </span>#00000006;

  }

  .prevnext-subtitle<span class="w"> </span>{

  <span class="w">  </span>color:<span class="w"> </span>var(--prevnext-color-text);

  <span class="w">  </span>filter:<span class="w"> </span>brightness(var(--prevnext-subtitle-brightness));

  <span class="w">  </span>font-size:<span class="w"> </span>.8rem;

  }

  .prevnext-title<span class="w"> </span>{

  <span class="w">  </span>color:<span class="w"> </span>var(--prevnext-color-text);

  <span class="w">  </span>font-size:<span class="w"> </span>1rem;

  }

  .prevnext-text<span class="w"> </span>{

  <span class="w">  </span>max-width:<span class="w"> </span>30vw;

  }

  <span class="nt">&lt;/style&gt;</span>


  <span class="nt">&lt;a</span><span class="w"> </span><span class="na">class=</span><span
  class="s">&#39;prev&#39;</span><span class="w"> </span><span class="na">href=</span><span
  class="s">&#39;/pygame-with-chatgpt&#39;</span><span class="nt">&gt;</span>



  <span class="w">    </span><span class="nt">&lt;svg</span><span class="w"> </span><span
  class="na">width=</span><span class="s">&quot;50px&quot;</span><span class="w">
  </span><span class="na">height=</span><span class="s">&quot;50px&quot;</span><span
  class="w"> </span><span class="na">viewbox=</span><span class="s">&quot;0 0 24 24&quot;</span><span
  class="w"> </span><span class="na">fill=</span><span class="s">&quot;none&quot;</span><span
  class="w"> </span><span class="na">xmlns=</span><span class="s">&quot;http://www.w3.org/2000/svg&quot;</span><span
  class="nt">&gt;</span>

  <span class="w">        </span><span class="nt">&lt;path</span><span class="w">
  </span><span class="na">d=</span><span class="s">&quot;M13.5 8.25L9.75 12L13.5 15.75&quot;</span><span
  class="w"> </span><span class="na">stroke=</span><span class="s">&quot;var(--prevnext-color-angle)&quot;</span><span
  class="w"> </span><span class="na">stroke-width=</span><span class="s">&quot;1.5&quot;</span><span
  class="w"> </span><span class="na">stroke-linecap=</span><span class="s">&quot;round&quot;</span><span
  class="w"> </span><span class="na">stroke-linejoin=</span><span class="s">&quot;round&quot;</span><span
  class="nt">&gt;</span><span class="w"> </span><span class="nt">&lt;/path&gt;</span>

  <span class="w">    </span><span class="nt">&lt;/svg&gt;</span>

  <span class="w">    </span><span class="nt">&lt;div</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-text&#39;</span><span class="nt">&gt;</span>

  <span class="w">        </span><span class="nt">&lt;p</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-subtitle&#39;</span><span
  class="nt">&gt;</span>prev<span class="nt">&lt;/p&gt;</span>

  <span class="w">        </span><span class="nt">&lt;p</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-title&#39;</span><span class="nt">&gt;</span>Pygame<span
  class="w"> </span>with<span class="w"> </span>chatgpt<span class="nt">&lt;/p&gt;</span>

  <span class="w">    </span><span class="nt">&lt;/div&gt;</span>

  <span class="nt">&lt;/a&gt;</span>


  <span class="nt">&lt;a</span><span class="w"> </span><span class="na">class=</span><span
  class="s">&#39;next&#39;</span><span class="w"> </span><span class="na">href=</span><span
  class="s">&#39;/&#39;</span><span class="nt">&gt;</span>


  <span class="w">    </span><span class="nt">&lt;div</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-text&#39;</span><span class="nt">&gt;</span>

  <span class="w">        </span><span class="nt">&lt;p</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-subtitle&#39;</span><span
  class="nt">&gt;</span>next<span class="nt">&lt;/p&gt;</span>

  <span class="w">        </span><span class="nt">&lt;p</span><span class="w"> </span><span
  class="na">class=</span><span class="s">&#39;prevnext-title&#39;</span><span class="nt">&gt;</span>Wyatt&#39;s<span
  class="w"> </span>Minecraft<span class="w"> </span>Documentary<span class="nt">&lt;/p&gt;</span>

  <span class="w">    </span><span class="nt">&lt;/div&gt;</span>

  <span class="w">    </span><span class="nt">&lt;svg</span><span class="w"> </span><span
  class="na">width=</span><span class="s">&quot;50px&quot;</span><span class="w">
  </span><span class="na">height=</span><span class="s">&quot;50px&quot;</span><span
  class="w"> </span><span class="na">viewbox=</span><span class="s">&quot;0 0 24 24&quot;</span><span
  class="w"> </span><span class="na">fill=</span><span class="s">&quot;none&quot;</span><span
  class="w"> </span><span class="na">xmlns=</span><span class="s">&quot;http://www.w3.org/2000/svg&quot;</span><span
  class="nt">&gt;</span>

  <span class="w">        </span><span class="nt">&lt;path</span><span class="w">
  </span><span class="na">d=</span><span class="s">&quot;M10.5 15.75L14.25 12L10.5
  8.25&quot;</span><span class="w"> </span><span class="na">stroke=</span><span class="s">&quot;var(--prevnext-color-angle)&quot;</span><span
  class="w"> </span><span class="na">stroke-width=</span><span class="s">&quot;1.5&quot;</span><span
  class="w"> </span><span class="na">stroke-linecap=</span><span class="s">&quot;round&quot;</span><span
  class="w"> </span><span class="na">stroke-linejoin=</span><span class="s">&quot;round&quot;</span><span
  class="nt">&gt;&lt;/path&gt;</span>

  <span class="w">    </span><span class="nt">&lt;/svg&gt;</span>

  <span class="nt">&lt;/a&gt;</span>

  </code></pre></div>


  </div>'
jinja: false
long_description: ''
now: 2023-07-08 14:57:35.749641
path: pages/beastiary.md
published: false
slug: beastiary
super_description: ''
tags:
- null
templateKey: ''
title: beastiary
today: 2023-07-08
---

## Bee

![](/bee.png)\\

 ## zombe


![](/zombe.png)<div class='prevnext'>

    <style type='text/css'>

    :root {
      --prevnext-color-text: #eefbfe;
      --prevnext-color-angle: #e1bd00c9;
      --prevnext-subtitle-brightness: 3;
    }
    [data-theme="light"] {
      --prevnext-color-text: #1f2022;
      --prevnext-color-angle: #ffeb00;
      --prevnext-subtitle-brightness: 3;
    }
    [data-theme="dark"] {
      --prevnext-color-text: #eefbfe;
      --prevnext-color-angle: #e1bd00c9;
      --prevnext-subtitle-brightness: 3;
    }
    .prevnext {
      display: flex;
      flex-direction: row;
      justify-content: space-around;
      align-items: flex-start;
    }
    .prevnext a {
      display: flex;
      align-items: center;
      width: 100%;
      text-decoration: none;
    }
    a.next {
      justify-content: flex-end;
    }
    .prevnext a:hover {
      background: #00000006;
    }
    .prevnext-subtitle {
      color: var(--prevnext-color-text);
      filter: brightness(var(--prevnext-subtitle-brightness));
      font-size: .8rem;
    }
    .prevnext-title {
      color: var(--prevnext-color-text);
      font-size: 1rem;
    }
    .prevnext-text {
      max-width: 30vw;
    }
    </style>
    
    <a class='prev' href='/pygame-with-chatgpt'>
    

        <svg width="50px" height="50px" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M13.5 8.25L9.75 12L13.5 15.75" stroke="var(--prevnext-color-angle)" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"> </path>
        </svg>
        <div class='prevnext-text'>
            <p class='prevnext-subtitle'>prev</p>
            <p class='prevnext-title'>Pygame with chatgpt</p>
        </div>
    </a>
    
    <a class='next' href='/'>
    
        <div class='prevnext-text'>
            <p class='prevnext-subtitle'>next</p>
            <p class='prevnext-title'>Wyatt's Minecraft Documentary</p>
        </div>
        <svg width="50px" height="50px" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M10.5 15.75L14.25 12L10.5 8.25" stroke="var(--prevnext-color-angle)" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
        </svg>
    </a>
  </div>