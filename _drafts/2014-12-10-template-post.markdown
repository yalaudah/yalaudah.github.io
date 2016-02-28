---
layout: post
title:  "Template Post"
date:   2014-12-10
comments: true
---

<p class="intro"><span class="dropcap">L</span>orem ipsum thor smash liege-bastogne-liege landbouwkrediet ombregt krabbe, rouleur derby is for lovers bonk giro gilbert bidon. Driedaagse de panne-koksijde monte paschi eroica, nevele gimondi berendries off the back cassette tenbosse.</p>


# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### Block Qoute:
<blockquote>Aenean lacinia bibendum nulla sed consectetur. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Cras mattis consectetur purus sit amet fermentum. Nulla vitae elit libero, a pharetra augue. Curabitur blandit tempus porttitor. Donec sed odio dui. Cras mattis consectetur purus sit amet fermentum.</blockquote>

Nullam quis risus eget urna mollis ornare vel eu leo. Cras mattis consectetur purus sit amet fermentum. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor.

## Unordered List
* List Item
* Longer List Item
  * Nested List Item
  * Nested Item
* List Item

## Ordered List
1. List Item
2. Longer List Item
    1. Nested OL Item
    2. Another Nested Item
3. List Item

## Definition List
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>


$$ x= \sin(\theta) $$ 

Bahamontes lanterne rouge normandie belgium. Fred paris-nice arrivere, for omnium commissaire ronde van vlaanderen horizontally stiff but vertically compliant muur, valkenberg jens paris-roubaix. Meyrueis belleville cavendish bianchi, rochefort echelon in soigneur ten dam omloop het volk, bettini aerts! Tour de mont aigoual cat among the pigeons rekelberg omloop het nieuwsblad paris-nice, dwars door vlaanderen coppi the colnago knockteberg anduze.

<img src="{{ 'http://static.pexels.com/photos/26754/pexels-photo-26754-large.jpg' | prepend: site.baseurl }}" alt=""> 

Kaperij lanterne rouge musette rund um koln bruges thor smash, geraardsbergen riis petacchi molteni pedaling squares. Virenque vande velde, valkenberg gutter pantani parcours gaul domestique, tilford campagnolo around madone. Bruyneel criterium ritte, gorgeous george the trousselier feed zone bruges nokere koerse, parcours gilbert garin? Anquetil valkenberg bettini cat among the pigeons.

<figure>
    <img src="{{ '/assets/img/touring.jpg' | prepend: site.baseurl }}" alt=""> 
    <figcaption>Fig1. - This is an example figcaption</figcaption>
</figure>

{% highlight html %}
<figure>
    <img src="{{ '/assets/img/touring.jpg' | prepend: site.baseurl }}" alt=""> 
    <figcaption>Fig1. - This is an example figcaption</figcaption>
</figure>
{% endhighlight %}


Campagnolo the hors delai de wolf as the toto turns venga venga venga, sanchez nys. Pantani hell of the north oude kwaremont nitto koppenberg, tiegemberg van steenbergen lombardie flamme rouge lemond e3 prijs vlaanderen.

Planckaert berg ter stene freire gorgeous george in rouleur derby, vaughters fabianese omloop het volk rouleur play rouleur derby. Bottechia petacchi, milan-san remo van summeren off the back cutters the cassette.

Nyvelocity pyrenees vande velde merckx. La fleche wallonne fixie pau, with muur hors categorie boonen aerts operacion puerto, topsport vlaanderen pereiro randonneur. This greek text is produced by rouleur derby, almost certainly the best fantasy cycling game in the world snob trousselier col du galibier, flanders venga venga venga suitcase of courage cutters kolobnev molenberg.


``` python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None
class SomeClass:
    pass
>>> message = '''interpreter
... prompt'''
```

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com





<div id="disqus_thread"></div>
<script>
    /**
     *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
     *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables
     */
    /*
    var disqus_config = function () {
        this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
        this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() {  // DON'T EDIT BELOW THIS LINE
        var d = document, s = d.createElement('script');
        
        s.src = '//yalaudah.disqus.com/embed.js';
        
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>