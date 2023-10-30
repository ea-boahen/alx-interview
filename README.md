# alx-interview

<h1>Project: 0x00. Pascal&#39;s Triangle | Accra Intranet</h1>

<h1 class="gap">0x00. Pascal&#39;s Triangle</h1>

    <div id="project_id" style="display: none" data-project-id="1213"></div>



      

        <div class="panel panel-default">
    <div class="panel-heading">
      <h3 class="panel-title">Concepts</h3>
    </div>
    <div class="panel-body">
      <p>
        <em>For this project, we expect you to look at this concept:</em>
      </p>

      <ul>
          <li>
            <a href="/concepts/100005">Technical interview</a>
          </li>
      </ul>
    </div>
  </div>


      <div class="panel panel-default" id="project-description">
  <div class="panel-body">
    
  </div>
</div>


      

      

        
          <h2 class="gap">Tasks</h2>

    <div data-role="task11539" data-position="15" id="task-num-0">
      <div class="panel panel-default task-card " id="task-11539">
  <span id="user_id" data-id="191685"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      0. Pascal&#39;s Triangle
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="191685"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create a function <code>def pascal_triangle(n):</code> that returns a list of lists of integers representing the Pascal&rsquo;s triangle of <code>n</code>:</p>

<ul>
<li>Returns an empty list if <code>n &lt;= 0</code></li>
<li>You can assume <code>n</code> will be always an integer</li>
</ul>

<pre><code>guillaume@ubuntu:~/0x00$ cat 0-main.py
#!/usr/bin/python3
&quot;&quot;&quot;
0-main
&quot;&quot;&quot;
pascal_triangle = __import__(&#39;0-pascal_triangle&#39;).pascal_triangle

def print_triangle(triangle):
    &quot;&quot;&quot;
    Print the triangle
    &quot;&quot;&quot;
    for row in triangle:
        print(&quot;[{}]&quot;.format(&quot;,&quot;.join([str(x) for x in row])))


if __name__ == &quot;__main__&quot;:
    print_triangle(pascal_triangle(5))

guillaume@ubuntu:~/0x00$ 
guillaume@ubuntu:~/0x00$ ./0-main.py
[1]
[1,1]
[1,2,1]
[1,3,3,1]
[1,4,6,4,1]
guillaume@ubuntu:~/0x00$ 
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-interview</code></li>
            <li>Directory: <code>0x00-pascal_triangle</code></li>
            <li>File: <code>0-pascal_triangle.py</code></li>
        </ul>
      </div>
