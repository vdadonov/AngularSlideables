AngularSlideables
=================

A “pure” Angular implementation of jQuery-style toggleSlide().

See https://jsfiddle.net/vdadonov/c25esktc/8/ for an example.

USAGE:

Link to the library in your index (or require.js), and add 'angularSlideables' to your app modules.

No CSS is necessary. Add the “slideable” class to any hidden, slideable content. Add a slide-toggle attribute to any trigger.

This directive currently without IDs.

EXAMPLES:

<pre><code>
<article ng-app="angularSlideables">
    <h1 slide-toggle >Click here for Hipster Ipsum.</h1>
    <div class="slideable">
        <p>Bespoke aesthetic Bushwick craft beer. Qui aesthetic butcher, cardigan ex scenester Neutra American Apparel mumblecore.</p>
        <p>Ethical adipisicing before they sold out, sriracha Thundercats cardigan dolor deep v placeat. Flannel tattooed meggings direct trade banh mi tousled sriracha. Portland VHS ut dreamcatcher. Butcher eu irony, Banksy leggings eiusmod Pinterest hashtag Etsy asymmetrical lo-fi Helvetica quis incididunt adipisicing. YOLO cliche minim mlkshk dreamcatcher excepteur, Austin McSweeney's.</p>
        <p>Coded @ Kinfolk Studios in Williamsburg, Brooklyn, 2013.</p>
    </div>
    <p>Your fresh artisinal Ipsum will appear above this paragraph. </p>
</article>
</code></pre>