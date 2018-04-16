---
ID: 245
post_title: Redirect
author: admin
post_excerpt: ""
layout: page
permalink: http://35.204.16.51/redirect/
published: true
post_date: 2018-04-16 21:45:03
---
<section class="main-container">
        <div class="main-wrapper">
                <h2>Home</h2>
                <?php
                        //Here we display a message if we are logged in!
                        if (isset($_SESSION['u_id'])) {
                                echo "You are logged in!";
                        }
                ?>
        </div>
</section>