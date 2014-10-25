listrap
=======

Listrap is a Bootstrap plugin for generate selectable lists by selecting item's thumbnail, ideal for mobile applications.

<h3>How to use</h3>

HTML

    <ul>
      <li>
          <div class="listrap-toggle">
              <span></span>
              <img src="http://lorempixel.com/60/60/people/?v=1" class="img-circle" />
          </div>
          <strong>My option</strong>
      </li>
      ...
    </ul>

JavaScript

    $("yourselector").listrap();
    
    
<h3>Methods</h3>

<h4>getSelection</h4>

Returns an array with <code>li</code> selected elements.
    
    var selection = $("yourselector").listrap().getSelection();
    
    
<h3>Events</h3>

<h4>selection-changed</h4>

Triggered when a item is selected. [selection] argument is optional.

    $("yourselector").listrap().on("selection-changed", function(selection) {
      console.log(selection);
    });
    
    
<h3>License</h3>

Licensed under MIT License.
http://opensource.org/licenses/MIT
