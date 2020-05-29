# BlogApp
<p><strong>Blog App</strong> is a Full Stack web application developed with best applications of RESTful Routing using Node.JS, Express.JS, Embedded JavaScript (EJS) and more.</p>
<h3>RESTful Routes:</h3>
<table>
<thead>
<tr>
<th>Name</th>
<th>Path</th>
<th>HTTP Verb</th>
<th>Purpose</th>
<th>Mongoose Method</th>
</tr>
</thead>
<tbody>
<tr>
<td>Index</td>
<td>/blogs</td>
<td>GET</td>
<td>List all blogs</td>
<td>Blog.find()</td>
</tr>
<tr>
<td>New</td>
<td>/blogs/new</td>
<td>GET</td>
<td>Show new blog form</td>
<td>N/A</td>
</tr>
<tr>
<td>Create</td>
<td>/blogs</td>
<td>POST</td>
<td>Create a new blog, then redirect somewhere</td>
<td>Blog.create()</td>
</tr>
<tr>
<td>Show</td>
<td>/blogs/:id</td>
<td>GET</td>
<td>Show info about one specific blog</td>
<td>Blog.findById()</td>
</tr>
<tr>
<td>Edit</td>
<td>/blogs/:id/edit</td>
<td>GET</td>
<td>Show edit form for one blog</td>
<td>Blog.findById()</td>
</tr>
<tr>
<td>Update</td>
<td>/blogs/:id</td>
<td>PUT</td>
<td>Update a particular blog, then redirect somewhere</td>
<td>Blog.findByIdAndUpdate()</td>
</tr>
<tr>
<td>Destroy</td>
<td>/blogs/:id</td>
<td>DELETE</td>
<td>Delete a particular blog, then redirect somewhere</td>
<td>Blog.findByIdAndRemove()</td>
</tr>
</tbody>
</table>
<h3>Description:</h3>
<ul>
<li><strong>app.js</strong> is the main file that is the heart of our NodeJS web application and contains the RESTful Routes defined for each event.</li>
<li><strong>views</strong> directory contains the relevant files, the EJS templates, that render on each event.</li>
<li><strong>public/css</strong> directory contains CSS to create better interface.</li>
<li><strong>package.json</strong> file contains the information towards the various frameworks that were installed within the course of this project.</li>
</ul>
<h3>Frameworks</h3>
<ul>
<li><strong>ExpressJS</strong> is used for Server Side Routing applications.</li>
<li><strong>MongooseJS</strong> is used for Back-End Database operations with MongoDB NoSQL Database.</li>
<li><strong>Body-Parser</strong> is used to Parse the data that was received as a result of HTTP POST request.</li>
<li><strong>Method-Override</strong> is used to override the HTTP verb to implement PUT and DELETE methods.</li>
<li><strong>Express.Static()</strong> is used to serve the Static files CSS, JS, etc. in the directory as specified.</li>
<li><strong>Sanitizer</strong> is used to sanitize the contents of HTML inputs and keeps the Database Safe.</li>
</ul>
