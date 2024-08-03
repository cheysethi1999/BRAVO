# Homepage: github.com/cheysethi1999/BRAVO
# Author: BRAVO_IT



<h1 id="socks5">socks5</h1>
<p><code class="language-plaintext highlighter-rouge">curl https://selivan.github.io/socks.txt | sudo bash</code></p>

<p>If you would like to manually set port and/or password:</p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">export </span><span class="nv">PORT</span><span class="o">=</span>8080<span class="p">;</span> <span class="nb">export </span><span class="nv">PASSWORD</span><span class="o">=</span>mypass
curl https://selivan.github.io/socks.txt | <span class="nb">sudo</span> <span class="nt">--preserve-env</span> bash
</code></pre></div></div>

<p>This creates self-hosted <a href="https://en.wikipedia.org/wiki/SOCKS">SOCKS5</a> server powered by <a href="http://www.inet.no/dante/">Dante</a>. Supported Linux distributions:</p>

<ul>
  <li>Ubuntu 16.04 Xenial</li>
  <li>Ubuntu 18.04 Bionic</li>
  <li>Ubuntu 20.04 Focal</li>
  <li>CentOS 7 and Oracle Linux 7.5 (thanks to <a href="https://github.com/vladsf">Vlad Safronov</a>)</li>
</ul>

<h1 id="shadowsocks">shadowsocks</h1>

<p><code class="language-plaintext highlighter-rouge">curl https://selivan.github.io/shadowsocks.txt | sudo bash</code></p>

<p>If you would like to manually set port and/or password:</p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">export </span><span class="nv">PORT</span><span class="o">=</span>8080<span class="p">;</span> <span class="nb">export </span><span class="nv">PASSWORD</span><span class="o">=</span>mypass
curl https://selivan.github.io/shadowsocks.txt | <span class="nb">sudo</span> <span class="nt">--preserve-env</span> bash
</code></pre></div></div>

<p>This creates self-hosted <a href="https://shadowsocks.org/">shadowsocks</a> server. Clients:</p>
<ul>
  <li>Android: <a href="https://play.google.com/store/apps/details?id=com.github.shadowsocks">shadowsocks by Max Lv</a></li>
  <li>Other devices: <a href="https://shadowsocks.org/en/download/clients.html">shadowsocks clients</a></li>
</ul>

<p>Supported Linux distributions:</p>

<ul>
  <li>Ubuntu 16.04 Xenial</li>
  <li>Ubuntu 18.04 Bionic</li>
  <li>CentOS 7 and RHEL 7 (thanks to Octavian Dodita octavian2204[anti-spam-dog]gmail.com )</li>
</ul>
