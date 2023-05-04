Download Link: https://assignmentchef.com/product/solved-cs701-module3-assignment
<br>
<ul>

 <li>When the term <em>lastName</em> is referenced in an assignment, please replace it with your last name.</li>

</ul>

<strong>You are strongly encouraged to add comments into your program!</strong>

Create a new folder named HW3_<em>lastName. </em>Write the following programs in this folder.

<h1>Part1 –   AngularJS Shopping Cart Application (60 Points)</h1>

Using AngularJS, modify the Shopping Cart application covered in the lecture as follows.

The initial layout of the application is shown below.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/255.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/255.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>The changes to the sample application are as follows:

<ul>

 <li>The total value of the ordered books is now displayed on the table header row last column. This value should change whenever the inputs affecting the total change.</li>

 <li>The title, quantity, and unit price are editable inputs. Changing the quantity or the unit price should be reflected in the line total and the order total.</li>

 <li>The Remove button removes the respective book from the model. The view is automatically updated.</li>

 <li>The New button will add a new book object to the model. The default title will be “New Book” with quantity 1 and unit price of 10.99 as shown below. Clicking on this button will insert one new book each time it is clicked. After one click, the layout is shown below.</li>

</ul>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/831.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/831.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>The Save button stores the list of current books and their state into Local Storage. When the application is loaded, check in the local storage first if the books are already stored. If they are, use the stored data for the application. If the item is not there in local storage, use the default list of books as shown in the first figure. Use a single key named <em>lastName_cart </em> in the local storage for managing the state of the shopping cart. Use <strong>AngularJS module</strong> for the application.

<h1>Part2 –   AngularJS Filters (40 Points)</h1>

Using AngularJS, write the filter <em>tokenize</em> that can take an optional argument for the delimiter. By default, the filter produces a comma separated string of the individual characters of the given input. If the delimiter is provided, the individual characters in the input string are separated by the specified delimiter. For example,

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/254.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/254.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Write the filter in a module. Now, use the filter to develop the Angular application. The controller provides the initial values for the two model properties, the input string and the delimiter string. Sample outputs are shown below.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/609.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/609.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/744.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.logicprohub.com/wp-content/uploads/2019/09/744.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>