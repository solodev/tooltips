# tooltips
Sometimes the User Experience (UX) of your website needs a nudge - a bit more information in case the user doesn't know where to go next. Tooltips allow you to add a bit more information to help guide your website visitors through the User Experience. In this tutorial, [Solodev](https://www.solodev.com/) provides you with the code to add tooltips to your website.

## Tutorial

For detailed instructions, view Solodev's [Add Context to Bullet Points with Tooltips](https://www.solodev.com/blog/web-design/add-context-to-bullet-points-with-tooltips.stml)

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/o093x1sz/).

## HTML

The tooltips contain the following basic HTML markup.
```
<section class="pricing-boxes">
                            <div class="container">
                                <div class="boxes-container">
                             
                                    <div class="row">
                                        <div class="col-md-4">
                                            <div class="pricing-item pricing-item1">
                                                <div class="pricing-box">
                                                    <div class="outside-content top-content">
                                                        <h2>
                                                            Basic
                                                        </h2>
                                                        <p class="price">
                                                            <sup>$</sup>99<span>/MO</span>
                                                        </p>
                                                        <p>
                                                            <span class="box-server">Starting at</span>
                                                        </p>
                                                    </div>
                                                    <div class="inside-content">
                                                        <p>
                                                          
                                                        </p>
                                                        <p class="buy-btn">
                                                            <a class="btn" onclick="ga('send', 'event', 'Pricing Page', 'try now click', 'try now button pricing page'); redirectTOPrice('small');">Try Now</a>
                                                        </p>
                                                    </div>
                                                    <div class="outside-content">
                                                        <ul>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes a flexible, highly scalable way to manage your contacts, leads, and opportunities." style="cursor: help; width:inherit;">
                                                                    Hosting &amp; CRM Included
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Storage is a simple and scalable way to store, access, and share data over the Internet." style="cursor: help; width:inherit;">
                                                                    10 GB Storage
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Additional memory allows more programs to run at one time and allows processes to run faster with more room to work with." style="cursor: help; width:inherit;">
                                                                    2 GB Memory
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes support via email and chat from our team of Technical Account Managers." style="cursor: help; width:inherit;">
                                                                    Email &amp; Chat Support
                                                                </div>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="col-md-4">
                                            <div class="pricing-item pricing-item1">
                                                <div class="pricing-box">
                                                    <div class="outside-content top-content">
                                                        <h2>
                                                            Team
                                                        </h2>
                                                        <p class="price">
                                                            <sup>$</sup>249<span>/MO</span>
                                                        </p>
                                                        <p>
                                                            <span class="box-server">Starting at</span>
                                                        </p>
                                                    </div>
                                                    <div class="inside-content">
                                                        <p>
                                                           
                                                        </p>
                                                        <p class="buy-btn">
                                                            <a class="btn" onclick="ga('send', 'event', 'Pricing Page', 'buy now click', 'buy now medium button pricing page'); redirectTOPrice('medium');">Buy Now</a>
                                                        </p>
                                                    </div>
                                                    <div class="outside-content">
                                                        <ul>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes a flexible, highly scalable way to manage your contacts, leads, and opportunities." style="cursor: help; width:inherit;">
                                                                    Hosting &amp; CRM Included
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Cloud storage is a simple and scalable way to store, access, and share data over the Internet." style="cursor: help; width:inherit;">
                                                                    50 GB Storage
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Additional memory allows more programs to run at one time and allows processes to run faster with more room to work with." style="cursor: help; width:inherit;">
                                                                    4 GB Memory
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes support via email and chat from our team of Technical Account Managers." style="cursor: help; width:inherit;">
                                                                    Email &amp; Chat Support
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes automated daily backups of your server instance(s) for increased security." style="cursor: help; width:inherit;">
                                                                    Daily Backups
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes a dedicated IP (Internet Protocol), a unique Internet address dedicated exclusively to your hosting account. This is in contrast to the normal configuration of several hosting accounts residing on a single server and sharing its IP address." style="cursor: help; width:inherit;">
                                                                    Dedicated IP
                                                                </div>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="col-md-4">
                                            <div class="pricing-item pricing-item2">
                                                <div class="pricing-box pricing-boxes2">
                                                    <div class="outside-content top-content">
                                                        <h2>
                                                            Enterprise
                                                        </h2>
                                                        <p class="price">
                                                            <sup>$</sup>1,499<span>/MO</span>
                                                        </p>
                                                        <p>
                                                            <span class="box-server">Starting at</span>
                                                        </p>
                                                    </div>
                                                    <div class="inside-content">
                                                        <p>
                                                           
                                                        </p>
                                                        <p class="buy-btn">
                                                            <a class="btn btn-white" onclick="ga('send', 'event', 'Pricing Page', 'buy now click', 'buy now large button pricing page'); redirectTOPrice('large');">buy now</a>
                                                        </p>
                                                    </div>
                                                    <div class="outside-content">
                                                        <ul>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes a flexible, highly scalable way to manage your contacts, leads, and opportunities." style="cursor: help; width:inherit;">
                                                                    Hosting &amp; CRM Included
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Distributes incoming traffic across multiple EC2 instances, in multiple Availability Zones. This increases the fault tolerance of your applications." style="cursor: help; width:inherit;">
                                                                    Load Balancer
                                                                </div>
                                                            </li><!--<li> <div class="qtip-div" help-data="Includes 3 T2 Large Server Instances that provide a baseline level of CPU performance with the ability to burst above the baseline." style="cursor: help; width:inherit;">3 Small Web Servers</div></li>
                        <li> <div class="qtip-div" help-data="Cloud storage is a simple and scalable way to store, access, and share data over the Internet. " style="cursor: help; width:inherit;">100 GB Storage</div></li>
                        <li> <div class="qtip-div" help-data="Additional memory allows more programs to run at one time and allows processes to run faster with more room to work with." style="cursor: help; width:inherit;">6 GB Memory</div></li>-->
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes 3 T2 Large Server Instances that provide a baseline level of CPU performance with the ability to burst above the baseline." style="cursor: help; width:inherit;">
                                                                    3 Large Web Servers
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Cloud storage is a simple and scalable way to store, access, and share data over the Internet." style="cursor: help; width:inherit;">
                                                                    50 GB Storage
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Additional memory allows more programs to run at one time and allows processes to run faster with more room to work with." style="cursor: help; width:inherit;">
                                                                    8 GB Memory
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes support via email and chat from our team of Technical Account Managers." style="cursor: help; width:inherit;">
                                                                    Email &amp; Chat Support
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes phone support with a member of our technical support staff." style="cursor: help; width:inherit;">
                                                                    Phone Support
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes training customized to the needs of your business." style="cursor: help; width:inherit;">
                                                                    1 Training Seat
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes annual performance and security assessments to keep you and your customers up and running at the highest levels of efficiency." style="cursor: help; width:inherit;">
                                                                    Annual Reviews
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes automated daily backups of your server instance(s) for increased security." style="cursor: help; width:inherit;">
                                                                    Daily Backups
                                                                </div>
                                                            </li>
                                                            <li>
                                                                <div class="qtip-div" help-data="Includes a dedicated IP (Internet Protocol), a unique Internet address dedicated exclusively to your hosting account. This is in contrast to the normal configuration of several hosting accounts residing on a single server and sharing its IP address." style="cursor: help; width:inherit;">
                                                                    Dedicated IP
                                                                </div>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                          
                            </div>
                        </section>
                    </div>
                </section>
                 </div>
```
## JavaScript

The following JavaScript is required to initialize the tooltips on hover.
```
$(document).ready(function() {
    $('.qtip-div[help-data]').qtip({ 
       content: {
        attr: 'help-data' // Tell qTip2 to look inside this attr for its content
       },      
        position: {
            my: 'center left',  // Position my top left...
            at: 'center right', // at the bottom right of...           
        },
        style: { 
          classes: 'qtip-tipsy myCustomClass'// Inherit from preset style        
       }
    });
  });
```

## CSS

All necessary CSS is included in tooltips.css

## External Includes

This tutorial includes the following third party resources.

```

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/qtip2/3.0.3/jquery.qtip.min.css">
<link rel="stylesheet" href="tooltips.css">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/qtip2/3.0.3/jquery.qtip.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
