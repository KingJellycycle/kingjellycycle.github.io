--- 
layout: page 
---
<div class="outer-container">
    <div class="container expandable alt-background">
        <div class="title center">{{ page.title }}</div>
        <hr>
        <div class="container center">
            <div class="post">
                <div class="entry">
                    {{ content }}
                </div>
                <div class="date">
                    Written on {{ page.date | date: "%B %e, %Y" }}
                </div>
            </div>
        </div>
    </div>
</div>