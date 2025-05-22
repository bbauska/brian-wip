# brian-wip
brian-wip description - pulling up sample code and going from there.

:sunny:

<table>
  <thead>
    <tr>
	  <th>Universal Selector</th>
	</tr>
  </thead>
  <tbody>
    <tr>
	  <td><b>Pattern</b></td>
	  <td>&ast;</td>
	</tr>
	<tr>
	  <td><b>Description</b></td>
	  <td>Matches any element name in the document's language. If a rule does not have an explicit selector, the universal selector is inferred.</td>
    </tr>
	<tr>
	  <td><b>Examples</b></td>
	  <td><pre>&ast; {color: red }<br>div &ast; p {color: blue;}</pre></td>
	</tr>
  </tbody>
</table>


<table>
  <thead>
    <tr>
	  <th> border-image </th>
	  <th> Inh. N Anim. P </th>
	</tr>
  </thead>
  <tbody>
    <tr>
	  <td><b>Values</b></td>
	  <td>&lt;border-image-source&gt; ‖  &lt;border-image-slice&gt; &lbrack; /<br>
	  &lt;border-image-width&gt; | / &lt;border-image-width&gt;? /<br>
	  &lt;border-image-outset&gt; &rbrack;? ‖ &lt;border-image-repeat&gt;</td>
	</tr>
	<tr>
	  <td><b>Initial value</b></td>
	  <td>See individual properties</td>
	</tr>
	<tr>
	  <td><b>Computed value</b></td>
	  <td>See individual properties</td>
	</tr>
	<tr>
	  <td><b>Applies to</b></td>
	  <td>See individual properties</td>
	</tr>
	<tr>
	  <td><b>Animatable</b></td>
	  <td>Refer to individual border-image properties to see which are animatable.</td>
	</tr>
	  <td><b>Description    </b></td>
	  <td>A shorthand property that defines the source, slicing pattern, border width, degree of extension,  
   and repetition of an image-based border. The syntax is somewhat unusual compared to the rest of CSS, so 
   take extra time with it. For example, three of the five values possible are slash-separated and must be 
   listed in a specific order.<br><br>Note that it is effectively impossible to take a 
   simple image (say, a star) and repeat it around the edges of an element. To create that effect, you must 
   create a single image that contains nine copies of the image you wish to repeat in a 3×3 grid. It may   
   also be necessary to set border-width (<i>not</i> border-imagewidth) to be large enough to show the    
   image, depending on the value of border-image-outset.</td>
    </tr>
	<tr>
	  <td><b>Examples</b></td>
	  <td>
<pre>div.starry {border-image;
  url(stargrid.png) 5px repeat;}
aside {border-image: url(asides.png)
  100 50 150 / 8 3 13 / 2 stretch round;}</pre>
      </td>
	</tr>
  </tbody>
</table>
