WordPress Post Simulator
=========================

This tool is for testing blocking functionality of [IP Location Block][IP-Location-Block]
against various access patterns such as comment post, pingback, XMLRPC and so 
on.

It emulates the specific requests from various countries, and shows the HTTP 
response codes and messages.

![WordPress Post Simulator][Simulator]

### Limitation: ###

This tool is built up with [AngularJS][AngularJS]. So the 
[Same-origin policy][SameOrigin] is applied to its requests.

[IP-Location-Block]: https://wordpress.org/plugins/ip-location-block/ "IP Location Block &#124; WordPress.org"
[AngularJS]:    https://angularjs.org/ "AngularJS — Superheroic JavaScript MVW Framework"
[SameOrigin]:   https://en.wikipedia.org/wiki/Same-origin_policy "Same-origin policy - Wikipedia, the free encyclopedia"
[Simulator]:    img/PostEmulator.png "WordPress Post Simulator"
