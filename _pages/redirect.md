---
ID: 231
post_title: Redirect
author: admin
post_excerpt: ""
layout: page
permalink: http://35.204.16.51/redirect/
published: true
post_date: 2018-04-16 13:16:52
---
<?php


                <h2>Redirect</h2>
                <?php
                        //Here we display a message if we are logged in!
                        if (isset($_SESSION['u_id'])) {
                                echo "You are logged in!";
                        }
                ?>