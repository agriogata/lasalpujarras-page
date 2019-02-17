---
title: 'Fair economy'
published: true
taxonomy:
    category:
        - energy
        - food
        - 'economia local'
        - electronic
    tag:
        - 'economia local'
        - food
        - energy
        - electronic
menu: 'Fair economy'
process:
    markdown: true
    twig: true
admin:
    children_display_order: collection
content:
    items:
        - '@self.children'
    limit: 5
    order:
        by: default
        dir: asc
        custom:
            - energy
            - food
            - electronic
    pagination: true
    continue_link: true
---

<head>
        <style>
            body{    
                background-attachment: fixed;
                width: auto;
            }
            a{
            text-decoration: none;
            color: white;
            }
            a:hover{
            color:grey;
            }
            a:active{
            }
            a:visited{
            }
        .container{
                width : auto%;
                margin: auto;
            }
        .list{
            border: 1px #ccc solid;
            }
            .list ul{
               list-style: square;
            }    
        .welcome{
                border-radius: 15px;
                 background-color: #20202c;
                 padding: 5px 10px;
                margin: 20px 0;
                color: white;
            }
            .faircoin{
            float: right;
            width: 10%;
            position: absolute;
            right: 20px;
            top: 90px;
                      }
            h1{
                color: white;
            }
            h2{
                color: white;
            }
            h3{
                color: white;
                font-size: 20px;
            }
            p{
                color: white;
            }
</style>
</head>
<div class= "body">
	<div class= "container">
		<div class="welcome">
    		<h1> Economia Local </h1>

			<p>here you will find an overview about products and services, that we are allready able to provide cooperativly, or 			on which we are working on. It is sorted by sections. When you have an idea what else we should organize together 				and you have even an idea.
			Just contact us
  			</p>
  </div>
  </div>
  </div>