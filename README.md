# JokeAPI
 Newman Summary Report     code.renderMarkdown table, code.renderMarkdown th, code.renderMarkdown td { border: 1px solid black; width: max-content; padding: .75rem; } .theme-dark { --background-color: #222; --bg-card-deck: #444444; --text-color: #ccd2d8; --tab-border: solid 1px #444; --success: #3c9372; --failure: #c24a3f; --warning: #d28c23; --info: #4083b6; --badge-outline: #3c9372; --badge-bg: #cdd3db; --badge-text: #ccd2d9; --failure-row: #c24a3f; --warning-row: #d28c23; --card-bg: #444; --card-footer: #4f5758; --form-input: #ececb5; --hov-text: #d2dae5; --h4-text: #ccd1d9; } .theme-light { --tab-border: solid 1px #fff; --text-color: #000000; --success: #42a745; --failure: #dc3544; --warning: #f4c10b; --info: #49a1b8; --badge-outline: #040411; --badge-bg: #f8f9fa; --badge-text: #fff; --failure-row: #f5c6cb; --warning-row: #ffeeba; --card-bg: #f7f7f7; --hov-text: #fff; --h4-text: #ffffff; } body { padding-top:30px; background-color: var(--background-color)!important; color: var(--text-color); } #execution-data { padding: 10px; border: var(--tab-border); border-top: none; } .nav-tabs { padding-top: 10px; height: 105px; overflow-y: auto; } body.theme-dark .card-header { background-color: #444; } body.theme-light .card-header { background-color: #f7f7f7; } .card-footer { padding: .75rem 1.25rem; background-color: var(--card-footer); } .card-deck { background-color: var(--bg-card-deck)!important; } .form-control { background: var(--form-input); } .custom-tab { padding: 10px 15px; margin-right: 0px; height: 47px; width: 69px; text-align: center; border: var(--tab-border); border-bottom: none; cursor:pointer; } body.theme-dark .text-white { color: #ccd2d9!important; } h4 { color: var(--h4-text); } body.theme-dark h1 { color: #ccd2da; } body.theme-dark .bg-light>td { background: #4f5858!important; } body.theme-dark .hljs { background: #0a0a0ab0!important; color: #8d8787!important; } .bg-info { background-color: var(--info)!important; } .bg-success { background-color: var(--success)!important; } .alert-success { background-color: var(--success)!important; } .alert-warning { background-color: var(--warning)!important; } .alert-info { background-color: var(--info)!important; } .bg-warning { background-color: var(--warning)!important; } .badge-warning { color: var(--badge-text)!important; background-color: var(--warning)!important; } .table-warning>td { background-color: var(--warning-row); } .alert-danger { background-color: var(--failure)!important; } body.theme-dark .alert-dark { background-color: #636467!important; } body.theme-dark .text-dark { color: #d1dae4!important; } body.theme-dark .badge-light { color: #212529; background-color: #cdd3db; } body.theme-light .badge-light { color: #212529; background-color: #f8f9fa; } body.theme-light .bg-danger { background-color: var(--failure)!important; } body.theme-dark .bg-danger { background-color: var(--failure)!important; } .table-danger>td { background-color: var(--failure-row); } body.theme-dark .table .thead-light th { background-color: #4f5858!important; border-color: #dee2e6!important; color: #ccd2d8!important; } .itPassed { background: var(--success); color: white; } .itFailed { background: var(--failure); color: white; } .resultsInfoPass { color: var(--success); padding-top: 4px; } .resultsInfoFail { color: var(--failure); padding-top: 4px; } .badge-outline-success { color: var(--success); border: 1px solid var(--success); background-color: transparent; } .badge-outline { color: var(--badge-outline); border: 1px solid var(--badge-outline); background-color: transparent; } .btn-outline-success { color: var(--success)!important; border-color: var(--success)!important; } .backToTop:hover { background-color: var(--success); border-color: var(--success); color: var(--hov-text)!important; } .btn-outline-success:hover { background-color: var(--success); border-color: var(--success); color: var(--hov-text)!important; } .btn-outline-secondary { background-color: var(--success)!important; color: var(--hov-text)!important; } body.theme-dark .env-heading { color: #ccd2d9!important; } body, html { height:100%; } .card { overflow:hidden; } body.theme-dark .card-body { background-color: #444; } body.theme-light .card-body { background-color: #f7f7f7; } body.theme-dark .card-body .bg-danger { background-color: var(--failure)!important; } body.theme-light .card-body .bg-danger { background-color: var(--failure)!important; } .card-body .rotate { z-index: 8; float: right; height: 100%; } .card-body .rotate i { color: #14141426; position: absolute; left: 0; left: auto; right: -10px; bottom: 0; display: block; -webkit-transform: rotate(-44deg); -moz-transform: rotate(-44deg); -o-transform: rotate(-44deg); -ms-transform: rotate(-44deg); transform: rotate(-44deg); } .dyn-height { max-height:350px; overflow-y:auto; } .nav-pills .nav-link.active { background-color: transparent!important; } .backToTop { display: none; position: fixed; bottom: 10px; right: 20px; z-index: 99; font-size: 15px; outline: none; cursor: pointer; padding: 15px; border-radius: 4px; } .card-header .fa { transition: .3s transform ease-in-out; } .card-header .collapsed .fa { transform: rotate(90deg); } .single-line-tabs { padding-top: 10px; height: 60px; } ::-webkit-scrollbar { width: 5px; } ::-webkit-scrollbar-track { background: #f1f1f1; } ::-webkit-scrollbar-thumb { background: #888; } ::-webkit-scrollbar-thumb:hover { background: #555; } /\* The switch - the box around the slider \*/ .switch { position: relative; display: inline-block; width: 44px; height: 20px; } /\* Hide default HTML checkbox \*/ .switch input { opacity: 0; width: 0; height: 0; } /\* The slider \*/ .slider { position: absolute; cursor: pointer; top: 0; left: 0; right: 0; bottom: 0; background-color: #ccc; -webkit-transition: 0.4s; transition: 0.4s; } .slider:before { position: absolute; content: ""; height: 20px; width: 20px; left: 0px; bottom: 4px; top: 0; bottom: 0; margin: auto 0; -webkit-transition: 0.4s; transition: 0.4s; box-shadow: 0 0px 15px #2020203d; background: white; background-repeat: no-repeat; background-position: center; } input:checked + .slider { background-color: #4083b6; } input:focus + .slider { box-shadow: 0 0 1px #4083b6; } input:checked + .slider:before { -webkit-transform: translateX(24px); -ms-transform: translateX(24px); transform: translateX(24px); background: white; background-repeat: no-repeat; background-position: center; } /\* Rounded sliders \*/ .slider.round { border-radius: 34px; } .slider.round:before { border-radius: 50%; } table.dataTable td, table.dataTable tr { vertical-align: middle; } body.theme-dark code { color: #ccd2d8!important; } body.theme-light code { color: #000000!important; } .text-wrap { word-wrap: break-word; min-width: 600px; max-width: 600px; white-space: normal; } function setTheme(themeName) { localStorage.setItem('theme', themeName); document.body.className = themeName; } function toggleTheme() { if (localStorage.getItem('theme') === 'theme-light') { setTheme('theme-dark'); } else { setTheme('theme-light'); } }

Light  Dark

*   [Summary](#pills-summary)
*   [Total Requests 8](#pills-requests)
*   [Failed Tests 8](#pills-failed)
*   [Skipped Tests 0](#pills-skipped)

Newman Run Dashboard
====================

##### Tuesday, 30 January 2024 18:05:45

###### Total Iterations

1
=

###### Total Assertions

0
=

###### Total Failed Tests

8
=

###### Total Skipped Tests

0
=

* * *

##### File Information

**Collection:** JokeAPI  

##### Collection Description

`A public API to deliver joy to the world!`

##### Timings and Data

**Total run duration:** 712ms  
**Total data received:** 0B  
**Average response time:** 0ms  

Summary Item

Total

Failed

Requests

8

8

Prerequest Scripts

0

0

Test Scripts

0

0

Assertions

0

0

Skipped Tests

0

\-

* * *

Go To Top

Expand All Failed Tests

  
  

#### Showing 8 Failures

[Iteration 1 - Error - JokeAPI - Random Joke](#)

##### **Failed Test:**

* * *

##### Assertion Error Message

    connect ECONNREFUSED 127.0.0.1:3000

[Iteration 1 - Error - JokeAPI - Specific Joke](#)

##### **Failed Test:**

* * *

##### Assertion Error Message

    runtime:extensions~request: request url is empty

[Iteration 1 - Error - JokeAPI - Filtered Joke By Type](#)

##### **Failed Test:**

* * *

##### Assertion Error Message

    runtime:extensions~request: request url is empty

[Iteration 1 - Error - JokeAPI - New Joke](#)

##### **Failed Test:**

* * *

##### Assertion Error Message

    Invalid URI "http:///jokes"

[Iteration 1 - Error - JokeAPI - Replace Joke](#)

##### **Failed Test:**

* * *

##### Assertion Error Message

    Invalid URI "http:///jokes/:id"

[Iteration 1 - Error - JokeAPI - Edit Joke](#)

##### **Failed Test:**

* * *

##### Assertion Error Message

    Invalid URI "http:///jokes/:id"

[Iteration 1 - Error - JokeAPI - A Joke](#)

##### **Failed Test:**

* * *

##### Assertion Error Message

    Invalid URI "http:///jokes/:id"

[Iteration 1 - Error - JokeAPI - All Jokes](#)

##### **Failed Test:**

* * *

##### Assertion Error Message

    Invalid URI "http:///jokes/all"

Go To Top

  
  

There are no skipped tests
==========================

  
  

Go To Top

Show Failed Iterations Expand Folders Expand Requests

##### 1 Iteration available to view

[Iteration: 1 - Random Joke](#)

##### Request Description

`Get a random joke from the Joke API`

##### Request Information

**Request Method:** GET  
**Request URL:** [http://localhost:3000/random/](http://localhost:3000/random/)  

##### Response Information

**Response Code:** \-  
**Mean time per request:** 0ms  
**Mean size per request:** 0B  

* * *

##### Test Pass Percentage

##### **No Tests for this request**

##### Request Headers

Header Name

Header Value

User-Agent

PostmanRuntime/7.36.1

Accept

\*/\*

Cache-Control

no-cache

Postman-Token

47207136-31bf-4b76-ac64-83f516be6d24

Host

localhost:3000

Accept-Encoding

gzip, deflate, br

Connection

keep-alive

##### Response Headers

##### Response Body

##### No Response Body for this request

##### Test Information

##### No Tests for this request

[Iteration: 1 - Specific Joke](#)

##### Request Description

`Responds with a single joke with the requested joke id. Provide the joke id as a path parameter.`

##### Request Information

**Request Method:** GET  
**Request URL:**  

##### Response Information

**Response Code:** \-  
**Mean time per request:** 0ms  
**Mean size per request:** 0B  

* * *

##### Test Pass Percentage

##### **No Tests for this request**

##### Request Headers

Header Name

Header Value

##### Response Headers

##### Response Body

##### No Response Body for this request

##### Test Information

##### No Tests for this request

[Iteration: 1 - Filtered Joke By Type](#)

##### Request Description

``Filters all the jokes by their joke type. Provide a query parameter for `type` and if the type exists, then you should get back all the jokes that match that type.``

##### Request Information

**Request Method:** GET  
**Request URL:**  

##### Response Information

**Response Code:** \-  
**Mean time per request:** 0ms  
**Mean size per request:** 0B  

* * *

##### Test Pass Percentage

##### **No Tests for this request**

##### Request Headers

Header Name

Header Value

##### Response Headers

##### Response Body

##### No Response Body for this request

##### Test Information

##### No Tests for this request

[Iteration: 1 - New Joke](#)

##### Request Description

``Create a new joke to add into the bank of jokes. Need to provide body parameters for `text` and `type`. Joke ID will be autogenerated.``

##### Request Information

**Request Method:** POST  
**Request URL:** [http://jokes](http://jokes)  

##### Response Information

**Response Code:** \-  
**Mean time per request:** 0ms  
**Mean size per request:** 0B  

* * *

##### Test Pass Percentage

##### **No Tests for this request**

##### Request Headers

Header Name

Header Value

User-Agent

PostmanRuntime/7.36.1

Accept

\*/\*

Cache-Control

no-cache

Postman-Token

83d27bac-147d-40f1-826f-7f831134c056

Host

Accept-Encoding

gzip, deflate, br

Connection

keep-alive

##### Response Headers

##### Response Body

##### No Response Body for this request

##### Test Information

##### No Tests for this request

[Iteration: 1 - Replace Joke](#)

##### Request Description

``Completely replace a joke based on the path parameter id specified. Provide the replacement values for the `text` and `type`.``

##### Request Information

**Request Method:** PUT  
**Request URL:** [http://jokes/:id](http://jokes/:id)  

##### Response Information

**Response Code:** \-  
**Mean time per request:** 0ms  
**Mean size per request:** 0B  

* * *

##### Test Pass Percentage

##### **No Tests for this request**

##### Request Headers

Header Name

Header Value

User-Agent

PostmanRuntime/7.36.1

Accept

\*/\*

Cache-Control

no-cache

Postman-Token

f54e55c2-36fb-4c58-a07b-d0fd7bda73d5

Host

Accept-Encoding

gzip, deflate, br

Connection

keep-alive

##### Response Headers

##### Response Body

##### No Response Body for this request

##### Test Information

##### No Tests for this request

[Iteration: 1 - Edit Joke](#)

##### Request Description

``Edit a joke for the id that is specified in the path parameter. Provide optional values for either the `text` or the `type`.``

##### Request Information

**Request Method:** PATCH  
**Request URL:** [http://jokes/:id](http://jokes/:id)  

##### Response Information

**Response Code:** \-  
**Mean time per request:** 0ms  
**Mean size per request:** 0B  

* * *

##### Test Pass Percentage

##### **No Tests for this request**

##### Request Headers

Header Name

Header Value

User-Agent

PostmanRuntime/7.36.1

Accept

\*/\*

Cache-Control

no-cache

Postman-Token

4714036e-ca35-4af4-b714-8162bd4abf8f

Host

Accept-Encoding

gzip, deflate, br

Connection

keep-alive

##### Response Headers

##### Response Body

##### No Response Body for this request

##### Test Information

##### No Tests for this request

[Iteration: 1 - A Joke](#)

##### Request Description

``Delete a joke rfom the bank of jokes based on the path parameter provided for the joke `id`. Will return an error if no jokes match the provided `id`.``

##### Request Information

**Request Method:** DELETE  
**Request URL:** [http://jokes/:id](http://jokes/:id)  

##### Response Information

**Response Code:** \-  
**Mean time per request:** 0ms  
**Mean size per request:** 0B  

* * *

##### Test Pass Percentage

##### **No Tests for this request**

##### Request Headers

Header Name

Header Value

User-Agent

PostmanRuntime/7.36.1

Accept

\*/\*

Cache-Control

no-cache

Postman-Token

29afb7c4-538d-42f0-b1aa-2714db35691b

Host

Accept-Encoding

gzip, deflate, br

Connection

keep-alive

##### Response Headers

##### Response Body

##### No Response Body for this request

##### Test Information

##### No Tests for this request

[Iteration: 1 - All Jokes](#)

##### Request Description

`Delete all jokes in the bank. DANGER. Authentication: Requires an API Key to perform this action.`

##### Request Information

**Request Method:** DELETE  
**Request URL:** [http://jokes/all](http://jokes/all)  

##### Response Information

**Response Code:** \-  
**Mean time per request:** 0ms  
**Mean size per request:** 0B  

* * *

##### Test Pass Percentage

##### **No Tests for this request**

##### Request Headers

Header Name

Header Value

User-Agent

PostmanRuntime/7.36.1

Accept

\*/\*

Cache-Control

no-cache

Postman-Token

c6f75a33-8907-41a2-b6c6-772371b2338e

Host

Accept-Encoding

gzip, deflate, br

Connection

keep-alive

##### Response Headers

##### Response Body

##### No Response Body for this request

##### Test Information

##### No Tests for this request

hljs.initHighlightingOnLoad(); (function () { var sliderChecked = true; if (localStorage.getItem('theme') === 'theme-light') { setTheme('theme-light'); sliderChecked = false; } else { setTheme('theme-dark'); sliderChecked = true; } $(document).ready( function () { document.getElementById('slider').checked = sliderChecked; }); })(); $(document).ready( function () { $('.datatable').DataTable({ "retrieve": true, "paging": false, "info": false, "fixedColumns": { "heightMatch": 'none' } }); }); $(document).ready(function() { $('\[data-toggle="tooltip"\]').tooltip({ trigger : 'hover' }) }) $('#openAll').on('click', function(e) { let clickCount = $(this).data("clickCount") || 1 switch (clickCount){ case 1: $('#folder-87799c51-6cf8-4b46-a1b0-3af1c016ba2b-iteration-0').removeClass('collapsed') $('#folder-collapse-87799c51-6cf8-4b46-a1b0-3af1c016ba2b-iteration-0').addClass('show') $('#openAll').html("Collapse Folders"); break; case 2: $('#folder-87799c51-6cf8-4b46-a1b0-3af1c016ba2b-iteration-0').addClass('collapsed') $('#folder-collapse-87799c51-6cf8-4b46-a1b0-3af1c016ba2b-iteration-0').removeClass('show') $('#openAll').html("Expand Folders"); break; } clickCount = clickCount > 1 ? 1 : ++clickCount; $(this).data("clickCount", clickCount) }) $('#openAllRequests').on('click', function(e) { let clickCount = $(this).data("clickCount") || 1 switch (clickCount){ case 1: $('#requests-fd15494d-41fe-4f3d-b460-f23d20da412b').removeClass('collapsed') $('#collapse-fd15494d-41fe-4f3d-b460-f23d20da412b').removeClass('collapsed') $('#requests-fd15494d-41fe-4f3d-b460-f23d20da412b').addClass('show') $('#collapse-fd15494d-41fe-4f3d-b460-f23d20da412b').addClass('show') $('#requests-ce41574a-2d97-4be6-bf1d-16df17cb4202').removeClass('collapsed') $('#collapse-ce41574a-2d97-4be6-bf1d-16df17cb4202').removeClass('collapsed') $('#requests-ce41574a-2d97-4be6-bf1d-16df17cb4202').addClass('show') $('#collapse-ce41574a-2d97-4be6-bf1d-16df17cb4202').addClass('show') $('#requests-1611174c-275d-4979-98e1-de4eb0d36c90').removeClass('collapsed') $('#collapse-1611174c-275d-4979-98e1-de4eb0d36c90').removeClass('collapsed') $('#requests-1611174c-275d-4979-98e1-de4eb0d36c90').addClass('show') $('#collapse-1611174c-275d-4979-98e1-de4eb0d36c90').addClass('show') $('#requests-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').removeClass('collapsed') $('#collapse-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').removeClass('collapsed') $('#requests-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').addClass('show') $('#collapse-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').addClass('show') $('#requests-efb840ae-be0f-4540-aac8-6810cd581f89').removeClass('collapsed') $('#collapse-efb840ae-be0f-4540-aac8-6810cd581f89').removeClass('collapsed') $('#requests-efb840ae-be0f-4540-aac8-6810cd581f89').addClass('show') $('#collapse-efb840ae-be0f-4540-aac8-6810cd581f89').addClass('show') $('#requests-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').removeClass('collapsed') $('#collapse-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').removeClass('collapsed') $('#requests-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').addClass('show') $('#collapse-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').addClass('show') $('#requests-5a477254-8da1-4865-a2ff-7820ccf5a956').removeClass('collapsed') $('#collapse-5a477254-8da1-4865-a2ff-7820ccf5a956').removeClass('collapsed') $('#requests-5a477254-8da1-4865-a2ff-7820ccf5a956').addClass('show') $('#collapse-5a477254-8da1-4865-a2ff-7820ccf5a956').addClass('show') $('#requests-7b243974-72d5-422f-ad79-26ee7e19183d').removeClass('collapsed') $('#collapse-7b243974-72d5-422f-ad79-26ee7e19183d').removeClass('collapsed') $('#requests-7b243974-72d5-422f-ad79-26ee7e19183d').addClass('show') $('#collapse-7b243974-72d5-422f-ad79-26ee7e19183d').addClass('show') $('#openAllRequests').html("Collapse Requests"); break; case 2: $('#requests-fd15494d-41fe-4f3d-b460-f23d20da412b').addClass('collapsed') $('#collapse-fd15494d-41fe-4f3d-b460-f23d20da412b').addClass('collapsed') $('#requests-fd15494d-41fe-4f3d-b460-f23d20da412b').removeClass('show') $('#collapse-fd15494d-41fe-4f3d-b460-f23d20da412b').removeClass('show') $('#requests-ce41574a-2d97-4be6-bf1d-16df17cb4202').addClass('collapsed') $('#collapse-ce41574a-2d97-4be6-bf1d-16df17cb4202').addClass('collapsed') $('#requests-ce41574a-2d97-4be6-bf1d-16df17cb4202').removeClass('show') $('#collapse-ce41574a-2d97-4be6-bf1d-16df17cb4202').removeClass('show') $('#requests-1611174c-275d-4979-98e1-de4eb0d36c90').addClass('collapsed') $('#collapse-1611174c-275d-4979-98e1-de4eb0d36c90').addClass('collapsed') $('#requests-1611174c-275d-4979-98e1-de4eb0d36c90').removeClass('show') $('#collapse-1611174c-275d-4979-98e1-de4eb0d36c90').removeClass('show') $('#requests-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').addClass('collapsed') $('#collapse-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').addClass('collapsed') $('#requests-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').removeClass('show') $('#collapse-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').removeClass('show') $('#requests-efb840ae-be0f-4540-aac8-6810cd581f89').addClass('collapsed') $('#collapse-efb840ae-be0f-4540-aac8-6810cd581f89').addClass('collapsed') $('#requests-efb840ae-be0f-4540-aac8-6810cd581f89').removeClass('show') $('#collapse-efb840ae-be0f-4540-aac8-6810cd581f89').removeClass('show') $('#requests-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').addClass('collapsed') $('#collapse-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').addClass('collapsed') $('#requests-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').removeClass('show') $('#collapse-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').removeClass('show') $('#requests-5a477254-8da1-4865-a2ff-7820ccf5a956').addClass('collapsed') $('#collapse-5a477254-8da1-4865-a2ff-7820ccf5a956').addClass('collapsed') $('#requests-5a477254-8da1-4865-a2ff-7820ccf5a956').removeClass('show') $('#collapse-5a477254-8da1-4865-a2ff-7820ccf5a956').removeClass('show') $('#requests-7b243974-72d5-422f-ad79-26ee7e19183d').addClass('collapsed') $('#collapse-7b243974-72d5-422f-ad79-26ee7e19183d').addClass('collapsed') $('#requests-7b243974-72d5-422f-ad79-26ee7e19183d').removeClass('show') $('#collapse-7b243974-72d5-422f-ad79-26ee7e19183d').removeClass('show') $('#openAllRequests').html("Expand Requests"); break; } clickCount = clickCount > 1 ? 1 : ++clickCount; $(this).data("clickCount", clickCount) }) $('#openAllSkipped').on('click', function(e) { let clickCount = $(this).data("clickCount") || 1 switch (clickCount){ case 1: $('#skipped-fd15494d-41fe-4f3d-b460-f23d20da412b').removeClass('collapsed') $('#skipped-collapse-fd15494d-41fe-4f3d-b460-f23d20da412b').removeClass('collapsed') $('#skipped-fd15494d-41fe-4f3d-b460-f23d20da412b').addClass('show') $('#skipped-collapse-fd15494d-41fe-4f3d-b460-f23d20da412b').addClass('show') $('#skipped-ce41574a-2d97-4be6-bf1d-16df17cb4202').removeClass('collapsed') $('#skipped-collapse-ce41574a-2d97-4be6-bf1d-16df17cb4202').removeClass('collapsed') $('#skipped-ce41574a-2d97-4be6-bf1d-16df17cb4202').addClass('show') $('#skipped-collapse-ce41574a-2d97-4be6-bf1d-16df17cb4202').addClass('show') $('#skipped-1611174c-275d-4979-98e1-de4eb0d36c90').removeClass('collapsed') $('#skipped-collapse-1611174c-275d-4979-98e1-de4eb0d36c90').removeClass('collapsed') $('#skipped-1611174c-275d-4979-98e1-de4eb0d36c90').addClass('show') $('#skipped-collapse-1611174c-275d-4979-98e1-de4eb0d36c90').addClass('show') $('#skipped-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').removeClass('collapsed') $('#skipped-collapse-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').removeClass('collapsed') $('#skipped-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').addClass('show') $('#skipped-collapse-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').addClass('show') $('#skipped-efb840ae-be0f-4540-aac8-6810cd581f89').removeClass('collapsed') $('#skipped-collapse-efb840ae-be0f-4540-aac8-6810cd581f89').removeClass('collapsed') $('#skipped-efb840ae-be0f-4540-aac8-6810cd581f89').addClass('show') $('#skipped-collapse-efb840ae-be0f-4540-aac8-6810cd581f89').addClass('show') $('#skipped-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').removeClass('collapsed') $('#skipped-collapse-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').removeClass('collapsed') $('#skipped-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').addClass('show') $('#skipped-collapse-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').addClass('show') $('#skipped-5a477254-8da1-4865-a2ff-7820ccf5a956').removeClass('collapsed') $('#skipped-collapse-5a477254-8da1-4865-a2ff-7820ccf5a956').removeClass('collapsed') $('#skipped-5a477254-8da1-4865-a2ff-7820ccf5a956').addClass('show') $('#skipped-collapse-5a477254-8da1-4865-a2ff-7820ccf5a956').addClass('show') $('#skipped-7b243974-72d5-422f-ad79-26ee7e19183d').removeClass('collapsed') $('#skipped-collapse-7b243974-72d5-422f-ad79-26ee7e19183d').removeClass('collapsed') $('#skipped-7b243974-72d5-422f-ad79-26ee7e19183d').addClass('show') $('#skipped-collapse-7b243974-72d5-422f-ad79-26ee7e19183d').addClass('show') $('#openAllSkipped').html("Collapse All Skipped Tests"); break; case 2: $('#skipped-fd15494d-41fe-4f3d-b460-f23d20da412b').addClass('collapsed') $('#skipped-collapse-fd15494d-41fe-4f3d-b460-f23d20da412b').addClass('collapsed') $('#skipped-fd15494d-41fe-4f3d-b460-f23d20da412b').removeClass('show') $('#skipped-collapse-fd15494d-41fe-4f3d-b460-f23d20da412b').removeClass('show') $('#skipped-ce41574a-2d97-4be6-bf1d-16df17cb4202').addClass('collapsed') $('#skipped-collapse-ce41574a-2d97-4be6-bf1d-16df17cb4202').addClass('collapsed') $('#skipped-ce41574a-2d97-4be6-bf1d-16df17cb4202').removeClass('show') $('#skipped-collapse-ce41574a-2d97-4be6-bf1d-16df17cb4202').removeClass('show') $('#skipped-1611174c-275d-4979-98e1-de4eb0d36c90').addClass('collapsed') $('#skipped-collapse-1611174c-275d-4979-98e1-de4eb0d36c90').addClass('collapsed') $('#skipped-1611174c-275d-4979-98e1-de4eb0d36c90').removeClass('show') $('#skipped-collapse-1611174c-275d-4979-98e1-de4eb0d36c90').removeClass('show') $('#skipped-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').addClass('collapsed') $('#skipped-collapse-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').addClass('collapsed') $('#skipped-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').removeClass('show') $('#skipped-collapse-4b45e0e7-0515-4a8b-8bc9-693d282a68f0').removeClass('show') $('#skipped-efb840ae-be0f-4540-aac8-6810cd581f89').addClass('collapsed') $('#skipped-collapse-efb840ae-be0f-4540-aac8-6810cd581f89').addClass('collapsed') $('#skipped-efb840ae-be0f-4540-aac8-6810cd581f89').removeClass('show') $('#skipped-collapse-efb840ae-be0f-4540-aac8-6810cd581f89').removeClass('show') $('#skipped-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').addClass('collapsed') $('#skipped-collapse-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').addClass('collapsed') $('#skipped-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').removeClass('show') $('#skipped-collapse-a7613c9d-c1cb-47f4-8eb1-4e31bd95e0d1').removeClass('show') $('#skipped-5a477254-8da1-4865-a2ff-7820ccf5a956').addClass('collapsed') $('#skipped-collapse-5a477254-8da1-4865-a2ff-7820ccf5a956').addClass('collapsed') $('#skipped-5a477254-8da1-4865-a2ff-7820ccf5a956').removeClass('show') $('#skipped-collapse-5a477254-8da1-4865-a2ff-7820ccf5a956').removeClass('show') $('#skipped-7b243974-72d5-422f-ad79-26ee7e19183d').addClass('collapsed') $('#skipped-collapse-7b243974-72d5-422f-ad79-26ee7e19183d').addClass('collapsed') $('#skipped-7b243974-72d5-422f-ad79-26ee7e19183d').removeClass('show') $('#skipped-collapse-7b243974-72d5-422f-ad79-26ee7e19183d').removeClass('show') $('#openAllSkipped').html("Expand All Skipped Tests"); break; } clickCount = clickCount > 1 ? 1 : ++clickCount; $(this).data("clickCount", clickCount) }) $('#openAllFailed').on('click', function(e) { let clickCount = $(this).data("clickCount") || 1 let failedItemContent let failedItemHeading switch (clickCount){ case 1: failedItemHeading = $('#fails-52bccb02-2bd2-4650-8ed9-bf22cda1fc54'); failedItemContent = $("#fails-collapse-52bccb02-2bd2-4650-8ed9-bf22cda1fc54"); failedItemHeading.removeClass('collapsed') failedItemContent.removeClass('collapsed') failedItemHeading.addClass('show') failedItemContent.addClass('show') failedItemHeading = $('#fails-e09937ff-b21e-42c5-a4be-39020c040ee1'); failedItemContent = $("#fails-collapse-e09937ff-b21e-42c5-a4be-39020c040ee1"); failedItemHeading.removeClass('collapsed') failedItemContent.removeClass('collapsed') failedItemHeading.addClass('show') failedItemContent.addClass('show') failedItemHeading = $('#fails-9f5e15b8-27c9-4da6-b510-c59a9a1d56df'); failedItemContent = $("#fails-collapse-9f5e15b8-27c9-4da6-b510-c59a9a1d56df"); failedItemHeading.removeClass('collapsed') failedItemContent.removeClass('collapsed') failedItemHeading.addClass('show') failedItemContent.addClass('show') failedItemHeading = $('#fails-2d200c78-afb0-47e6-a675-2ec9191087ba'); failedItemContent = $("#fails-collapse-2d200c78-afb0-47e6-a675-2ec9191087ba"); failedItemHeading.removeClass('collapsed') failedItemContent.removeClass('collapsed') failedItemHeading.addClass('show') failedItemContent.addClass('show') failedItemHeading = $('#fails-5d2dd874-4b21-423f-9586-e7c6e540c42e'); failedItemContent = $("#fails-collapse-5d2dd874-4b21-423f-9586-e7c6e540c42e"); failedItemHeading.removeClass('collapsed') failedItemContent.removeClass('collapsed') failedItemHeading.addClass('show') failedItemContent.addClass('show') failedItemHeading = $('#fails-1356f42e-c752-4199-a129-04d689d1fdf2'); failedItemContent = $("#fails-collapse-1356f42e-c752-4199-a129-04d689d1fdf2"); failedItemHeading.removeClass('collapsed') failedItemContent.removeClass('collapsed') failedItemHeading.addClass('show') failedItemContent.addClass('show') failedItemHeading = $('#fails-33e57a35-9fe3-4406-8667-268f179a3016'); failedItemContent = $("#fails-collapse-33e57a35-9fe3-4406-8667-268f179a3016"); failedItemHeading.removeClass('collapsed') failedItemContent.removeClass('collapsed') failedItemHeading.addClass('show') failedItemContent.addClass('show') failedItemHeading = $('#fails-8a8aecd8-06e7-4bfb-9930-93a9d38c202a'); failedItemContent = $("#fails-collapse-8a8aecd8-06e7-4bfb-9930-93a9d38c202a"); failedItemHeading.removeClass('collapsed') failedItemContent.removeClass('collapsed') failedItemHeading.addClass('show') failedItemContent.addClass('show') $('#openAllFailed').html("Collapse All Failed Tests"); break; case 2: failedItemHeading = $('#fails-52bccb02-2bd2-4650-8ed9-bf22cda1fc54'); failedItemContent = $("#fails-collapse-52bccb02-2bd2-4650-8ed9-bf22cda1fc54"); failedItemHeading.removeClass('show') failedItemContent.removeClass('show') failedItemHeading.addClass('collapsed') failedItemContent.addClass('collapsed') failedItemHeading = $('#fails-e09937ff-b21e-42c5-a4be-39020c040ee1'); failedItemContent = $("#fails-collapse-e09937ff-b21e-42c5-a4be-39020c040ee1"); failedItemHeading.removeClass('show') failedItemContent.removeClass('show') failedItemHeading.addClass('collapsed') failedItemContent.addClass('collapsed') failedItemHeading = $('#fails-9f5e15b8-27c9-4da6-b510-c59a9a1d56df'); failedItemContent = $("#fails-collapse-9f5e15b8-27c9-4da6-b510-c59a9a1d56df"); failedItemHeading.removeClass('show') failedItemContent.removeClass('show') failedItemHeading.addClass('collapsed') failedItemContent.addClass('collapsed') failedItemHeading = $('#fails-2d200c78-afb0-47e6-a675-2ec9191087ba'); failedItemContent = $("#fails-collapse-2d200c78-afb0-47e6-a675-2ec9191087ba"); failedItemHeading.removeClass('show') failedItemContent.removeClass('show') failedItemHeading.addClass('collapsed') failedItemContent.addClass('collapsed') failedItemHeading = $('#fails-5d2dd874-4b21-423f-9586-e7c6e540c42e'); failedItemContent = $("#fails-collapse-5d2dd874-4b21-423f-9586-e7c6e540c42e"); failedItemHeading.removeClass('show') failedItemContent.removeClass('show') failedItemHeading.addClass('collapsed') failedItemContent.addClass('collapsed') failedItemHeading = $('#fails-1356f42e-c752-4199-a129-04d689d1fdf2'); failedItemContent = $("#fails-collapse-1356f42e-c752-4199-a129-04d689d1fdf2"); failedItemHeading.removeClass('show') failedItemContent.removeClass('show') failedItemHeading.addClass('collapsed') failedItemContent.addClass('collapsed') failedItemHeading = $('#fails-33e57a35-9fe3-4406-8667-268f179a3016'); failedItemContent = $("#fails-collapse-33e57a35-9fe3-4406-8667-268f179a3016"); failedItemHeading.removeClass('show') failedItemContent.removeClass('show') failedItemHeading.addClass('collapsed') failedItemContent.addClass('collapsed') failedItemHeading = $('#fails-8a8aecd8-06e7-4bfb-9930-93a9d38c202a'); failedItemContent = $("#fails-collapse-8a8aecd8-06e7-4bfb-9930-93a9d38c202a"); failedItemHeading.removeClass('show') failedItemContent.removeClass('show') failedItemHeading.addClass('collapsed') failedItemContent.addClass('collapsed') $('#openAllFailed').html("Expand All Failed Tests"); break; } clickCount = clickCount > 1 ? 1 : ++clickCount; $(this).data("clickCount", clickCount) }) function isJSON(data) { var ret = true; try { JSON.parse(data); }catch(e) { ret = false; } return ret; } function isXML(data) { return (data.length > 0 && data\[0\] === '<'); } // see https://gist.github.com/sente/1083506/d2834134cd070dbcc08bf42ee27dabb746a1c54d#gistcomment-2254622 function formatXML(data) { const PADDING = ' '.repeat(2); // set desired indent size here const reg = /(>)(<)(\\/\*)/g; let pad = 0; xml = data.replace(reg, '$1\\r\\n$2$3'); return xml.split('\\r\\n').map((node, index) => { let indent = 0; if (node.match(/.+<\\/\\w\[^>\]\*>$/)) { indent = 0; } else if (node.match(/^<\\/\\w/) && pad > 0) { pad -= 1; } else if (node.match(/^<\\w\[^>\]\*\[^\\/\]>.\*$/)) { indent = 1; } else { indent = 0; } pad += indent; return PADDING.repeat(pad - indent) + node; }).join('\\r\\n'); } $(".prettyPrint").each(function () { var data = $(this).text(); // Verify whether data is JSON if(isJSON(data)) { obj = JSON.parse(data); data = JSON.stringify(obj, null, 2); } else if(isXML(data)) { data = formatXML(data); } $(this).text(data); }); var clipboard = new ClipboardJS('.copyButton'); clipboard.on('success', function(e) { e.clearSelection(); $(".copyButton").addClass("bg-success text-white") e.trigger.textContent = '✔ Copied!'; window.setTimeout(function() { $(".copyButton").removeClass("bg-success text-white") e.trigger.textContent = 'Copy to Clipboard'; }, 2000); }); clipboard.on('error', function(e) { e.clearSelection(); $(".copyButton").addClass("bg-danger text-white") e.trigger.textContent = '✗ Not Copied'; window.setTimeout(function() { $(".copyButton").removeClass("bg-danger text-white") e.trigger.textContent = 'Copy to Clipboard'; }, 2000); }); const remarkable = new Remarkable(); const descriptions = document.querySelectorAll(".renderMarkdown"); descriptions.forEach(description => { description.innerHTML = renderHtmlFromMarkdown(description.textContent); }); function renderHtmlFromMarkdown(markdown) { return remarkable.render(trim(markdown)); } function trim(string) { return string ? string.replace(/^ +| +$/gm, "") : string; } window.onscroll = function() {scrollFunction()}; function scrollFunction() { if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) { document.getElementById("topOfRequestsScreen").style.display = "block"; document.getElementById("topOfFailuresScreen").style.display = "block"; document.getElementById("topOfSkippedScreen").style.display = "block"; document.getElementById("openAll").style.display = "none"; document.getElementById("openAllRequests").style.display = "none"; document.getElementById("showOnlyFailures").style.display = "none"; document.getElementById("openAllFailed").style.display = "none"; } else { document.getElementById("topOfRequestsScreen").style.display = "none"; document.getElementById("topOfFailuresScreen").style.display = "none"; document.getElementById("topOfSkippedScreen").style.display = "none"; document.getElementById("openAll").style.display = "block"; document.getElementById("openAllRequests").style.display = "block"; document.getElementById("showOnlyFailures").style.display = "block"; document.getElementById("openAllFailed").style.display = "block"; } } function topFunction() { document.body.scrollTop = 0; document.documentElement.scrollTop = 0; } "use strict"; window.onload = function () { // set display for all blocks of response var allItems = document.querySelectorAll('\[class\*=iteration-\]'); allItems.forEach(function(elem){ elem.style.display = 'block'; }); let totalIterations = 1; let menu = document.querySelector('#execution-menu .nav'); for(var i = 0; i < totalIterations; i++) { let li = document.createElement('li'); li.appendChild(document.createTextNode((i + 1))); li.setAttribute('id', 'iteration-' + i); li.classList.add("custom-tab"); li.classList.add("itPassed"); li.addEventListener('click', function() { //set display to none for all except row let allItems = document.querySelectorAll('\[class\*=iteration-\]:not(.row)'); allItems.forEach(function(elem) { elem.style.display = 'none'; }) let allMenus = document.querySelectorAll('\[id\*=iteration-\]'); allMenus.forEach(function(elem){ elem.style.borderBottom = 'none'; }) this.style.borderBottom = 'solid 3px #032a33'; let items = document.querySelectorAll("." + this.id + ':not(.row)'); items.forEach(function(elem) { elem.style.display = elem.style.display == 'block' ? 'none' : 'block'; }) }); menu.appendChild(li); } //shows first tab data document.getElementById('iteration-0').click(); document.getElementById('iterationSelected').innerHTML = \`Iteration ${document.getElementById('iteration-0').innerHTML} selected\` } $(document).ready(function(){ $(function() { $("#iterationList li").click(function() { document.getElementById('iterationSelected').innerHTML = "Iteration " + this.innerHTML + " selected" }); }); }); $("#filterInput").on("input paste", function() { var value = $(this).val(); $("#iterationList li").filter(function() { $("#showOnlyFailures").data("clickCount") ? $("#showOnlyFailures").click():null; $(this).toggle($(this).text().indexOf(value) > -1) }); }); $('#showOnlyFailures').on('click', function(e) { let clickCount = $(this).data("clickCount") || 1 $("#filterInput").val()!="" && clickCount==1 ? $("#filterInput").val('').trigger('input'): null; let selectedIteration = $('#iterationList li').filter(function () { return $(this).css('border-bottom').indexOf("solid") > -1 && $(this).hasClass('itFailed'); }); selectedIteration.length || clickCount > 1 ? null : $("#iterationList li.itFailed")\[0\].click() $("#iterationList li.itPassed").toggle() $("div.bg-success \[id\*=requests\]").parents('\[class^="row iteration-"\]').toggle(); clickCount = clickCount > 1 ? 1 : ++clickCount; clickCount > 1 ? $("#showOnlyFailures").html("Show All Iterations") : $("#showOnlyFailures").html("Show Failed Iterations"); $(this).data("clickCount", clickCount) })
