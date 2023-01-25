<h1> Printf Project</h1>
<p><b>Description</b></p>
<p>This team project is part of the first year curriculum of ALX. _printf replicates the C standard library printf() function.</p>
<ul>
<p>What you should learn from this project:</p>
<li>How to use git in a team setting</li>
<li>Applying variadic functions to a big project</li>
<li>The complexities of printf</li>
<li>Managing a lot of files and finding a good workflow</li>
</ul>
<h2>Prototype</h2>
<code>int _printf(const char *format, ...);</code>
<h3>Usage</h3>
<ul>
<li>Prints a string to the standard output, according to a given format</li>
<li>All files were created and compiled on Ubuntu 14.04.4 LTS using GCC 4.8.4 with the command <code>gcc -Wall -Werror -Wextra -pedantic *.c</code></li>
<li>Returns the number of characters in the output string on success, -1 otherwise</li>
<li>Call it this way:<code> _printf("format string", arguments...)</code> where <code>format string</code> can contain conversion specifiers and flags, along with regular characters</li>
</ul>
<h3>Examples</h3>
<ul>
<li><code>_printf("Hello, main\n")</code> prints "Hello, Main", followed by a new line</li>
<li><code>_printf("%s", "Hello")</code> prints "Hello"</li>
<li><code>_printf("This is a number: %d", 98)</code> prints "This is a number: 98"</li>
</ul>
