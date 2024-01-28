<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-mongoose---embedded-web-server--embedded-networking-library" class="anchor" aria-hidden="true" tabindex="-1" href="#mongoose---embedded-web-server--embedded-networking-library"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mongoose - 嵌入式 Web 服务器/嵌入式网络库</font></font></h1>
<p dir="auto"><a href="https://opensource.org/licenses/gpl-2.0.php" rel="nofollow"><img src="https://camo.githubusercontent.com/48ac5e5cefa5d1ec919b15644166664ff9d8d021f43265ee0a8763a56a300abe/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d47504c76322532306f72253230436f6d6d65726369616c2d677265656e2e737667" alt="许可证：GPLv2/商业" data-canonical-src="https://img.shields.io/badge/License-GPLv2%20or%20Commercial-green.svg" style="max-width: 100%;"></a>
<a href="https://github.com/cesanta/mongoose/actions"><img src="https://github.com/cesanta/mongoose/workflows/build/badge.svg" alt="构建状态" style="max-width: 100%;"></a>
<a href="https://codecov.io/gh/cesanta/mongoose" rel="nofollow"><img src="https://camo.githubusercontent.com/acc1bf9b67fc8c8cbcd13b71e3d9d0233762b01a624b0894365f975de66e4932/68747470733a2f2f636f6465636f762e696f2f67682f636573616e74612f6d6f6e676f6f73652f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="代码覆盖率" data-canonical-src="https://codecov.io/gh/cesanta/mongoose/branch/master/graph/badge.svg" style="max-width: 100%;"></a>
<a href="https://bugs.chromium.org/p/oss-fuzz/issues/list?sort=-opened&amp;can=1&amp;q=proj:mongoose" rel="nofollow"><img src="https://camo.githubusercontent.com/96965b85efcf5134ab936da42ad330459095c7f505cd513795ca5258eb6ce660/68747470733a2f2f6f73732d66757a7a2d6275696c642d6c6f67732e73746f726167652e676f6f676c65617069732e636f6d2f6261646765732f6d6f6e676f6f73652e737667" alt="模糊测试状态" data-canonical-src="https://oss-fuzz-build-logs.storage.googleapis.com/badges/mongoose.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mongoose 是一个 C/C++ 网络库。</font><font style="vertical-align: inherit;">它为 TCP、UDP、HTTP、WebSocket、MQTT 实现事件驱动的非阻塞 API。</font><font style="vertical-align: inherit;">它专为连接设备并使它们上线而设计。</font><font style="vertical-align: inherit;">自 2004 年上市以来，被大量开源和商业产品使用 - 它甚至在国际空间站上运行！</font><font style="vertical-align: inherit;">Mongoose 使嵌入式网络编程变得快速、健壮且简单。</font><font style="vertical-align: inherit;">特点包括：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跨平台：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于 Linux/UNIX、MacOS、Windows、Android</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于 STM32、NXP、ESP32、NRF52、TI、Microchip 等</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编写一次代码 - 它在任何地方都可以工作</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非常适合统一整个公司的网络基础设施代码</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置协议：普通 TCP/UDP、SNTP、HTTP、MQTT、Websocket</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对 mbedTLS 和 OpenSSL 的 SSL/TLS 支持</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异步 DNS 解析器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">静态和运行时占用空间极小</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">源代码符合 ISO C 和 ISO C++ 标准</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非常容易集成：只需将文件复制</font></font><code>mongoose.c</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到</font></font><code>mongoose.h</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">源代码树中即可。</font><font style="vertical-align: inherit;">查看
</font></font><a href="https://mongoose.ws/documentation/#2-minute-integration-guide" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具体步骤</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可在任何具有套接字 API 的环境中工作，例如 LwIP、Zephyr、Azure</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置 TCP/IP 堆栈，带有适用于裸机或 RTOS 系统的驱动程序
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用驱动程序：STM32F、STM32H；</font><font style="vertical-align: inherit;">恩智浦 RT1xxx；</font><font style="vertical-align: inherit;">德州仪器TM4C；</font><font style="vertical-align: inherit;">微芯片 SAME54；</font><font style="vertical-align: inherit;">维智网W5500</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">裸机
</font></font><a href="/cesanta/mongoose/blob/master/examples/stm32/nucleo-f429zi-baremetal"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nucleo-F429ZI</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上的完整 Web 设备仪表板只有 6 个文件</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为比较，CubeIDE 生成的 HTTP 示例有 400 多个文件</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置 TLS 1.3 服务器端支持</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不依赖任何其他软件来实现联网</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">STM32H5、STM32H7 等即将推出的内置固件更新</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">详细的</font></font><a href="https://mongoose.ws/documentation/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户指南、API 参考和大量教程</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-usage" class="anchor" aria-hidden="true" tabindex="-1" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建一个提供目录服务的简单 Web 服务器。</font><font style="vertical-align: inherit;">HTTP 服务器的行为由其事件处理函数指定：</font></font></p>
<div class="highlight highlight-source-c notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">#include</span> <span class="pl-s">"mongoose.h"</span>

<span class="pl-smi">int</span> <span class="pl-en">main</span>(<span class="pl-smi">void</span>) {
  <span class="pl-k">struct</span> <span class="pl-smi">mg_mgr</span> <span class="pl-s1">mgr</span>;  <span class="pl-c">// Declare event manager</span>
  <span class="pl-en">mg_mgr_init</span>(<span class="pl-c1">&amp;</span><span class="pl-s1">mgr</span>);  <span class="pl-c">// Initialise event manager</span>
  <span class="pl-en">mg_http_listen</span>(<span class="pl-c1">&amp;</span><span class="pl-s1">mgr</span>, <span class="pl-s">"http://0.0.0.0:8000"</span>, <span class="pl-s1">fn</span>, <span class="pl-c1">NULL</span>);  <span class="pl-c">// Setup listener</span>
  <span class="pl-k">for</span> (;;) {
    <span class="pl-en">mg_mgr_poll</span>(<span class="pl-c1">&amp;</span><span class="pl-s1">mgr</span>, <span class="pl-c1">1000</span>);  <span class="pl-c">// Run an infinite event loop</span>
  }
  <span class="pl-k">return</span> <span class="pl-c1">0</span>;
}

<span class="pl-c">// HTTP server event handler function</span>
<span class="pl-smi">void</span> <span class="pl-en">fn</span>(<span class="pl-k">struct</span> <span class="pl-smi">mg_connection</span> <span class="pl-c1">*</span><span class="pl-s1">c</span>, <span class="pl-smi">int</span> <span class="pl-s1">ev</span>, <span class="pl-smi">void</span> <span class="pl-c1">*</span><span class="pl-s1">ev_data</span>) {
  <span class="pl-k">if</span> (<span class="pl-s1">ev</span> <span class="pl-c1">==</span> <span class="pl-c1">MG_EV_HTTP_MSG</span>) {
    <span class="pl-k">struct</span> <span class="pl-smi">mg_http_message</span> <span class="pl-c1">*</span><span class="pl-s1">hm</span> <span class="pl-c1">=</span> (<span class="pl-k">struct</span> <span class="pl-smi">mg_http_message</span> <span class="pl-c1">*</span>) <span class="pl-s1">ev_data</span>;
    <span class="pl-k">struct</span> <span class="pl-smi">mg_http_serve_opts</span> <span class="pl-s1">opts</span> <span class="pl-c1">=</span> { .<span class="pl-c1">root_dir</span> <span class="pl-c1">=</span> <span class="pl-s">"./web_root/"</span> };
    <span class="pl-en">mg_http_serve_dir</span>(<span class="pl-s1">c</span>, <span class="pl-s1">hm</span>, <span class="pl-c1">&amp;</span><span class="pl-s1">opts</span>);
  }
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#include &quot;mongoose.h&quot;

int main(void) {
  struct mg_mgr mgr;  // Declare event manager
  mg_mgr_init(&amp;mgr);  // Initialise event manager
  mg_http_listen(&amp;mgr, &quot;http://0.0.0.0:8000&quot;, fn, NULL);  // Setup listener
  for (;;) {
    mg_mgr_poll(&amp;mgr, 1000);  // Run an infinite event loop
  }
  return 0;
}

// HTTP server event handler function
void fn(struct mg_connection *c, int ev, void *ev_data) {
  if (ev == MG_EV_HTTP_MSG) {
    struct mg_http_message *hm = (struct mg_http_message *) ev_data;
    struct mg_http_serve_opts opts = { .root_dir = &quot;./web_root/&quot; };
    mg_http_serve_dir(c, hm, &amp;opts);
  }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTP 服务器实现了返回当前时间的 REST API。</font><font style="vertical-align: inherit;">JSON 格式：</font></font></p>
<div class="highlight highlight-source-c notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">static</span> <span class="pl-smi">void</span> <span class="pl-en">fn</span>(<span class="pl-k">struct</span> <span class="pl-smi">mg_connection</span> <span class="pl-c1">*</span><span class="pl-s1">c</span>, <span class="pl-smi">int</span> <span class="pl-s1">ev</span>, <span class="pl-smi">void</span> <span class="pl-c1">*</span><span class="pl-s1">ev_data</span>) {
  <span class="pl-k">if</span> (<span class="pl-s1">ev</span> <span class="pl-c1">==</span> <span class="pl-c1">MG_EV_HTTP_MSG</span>) {
    <span class="pl-k">struct</span> <span class="pl-smi">mg_http_message</span> <span class="pl-c1">*</span><span class="pl-s1">hm</span> <span class="pl-c1">=</span> (<span class="pl-k">struct</span> <span class="pl-smi">mg_http_message</span> <span class="pl-c1">*</span>) <span class="pl-s1">ev_data</span>;
    <span class="pl-k">if</span> (<span class="pl-en">mg_http_match_uri</span>(<span class="pl-s1">hm</span>, <span class="pl-s">"/api/time/get"</span>)) {
      <span class="pl-en">mg_http_reply</span>(<span class="pl-s1">c</span>, <span class="pl-c1">200</span>, <span class="pl-s">""</span>, <span class="pl-s">"{%m:%lu}\n"</span>, <span class="pl-en">MG_ESC</span>(<span class="pl-s">"time"</span>), <span class="pl-en">time</span>(<span class="pl-c1">NULL</span>));
    } <span class="pl-k">else</span> {
      <span class="pl-en">mg_http_reply</span>(<span class="pl-s1">c</span>, <span class="pl-c1">500</span>, <span class="pl-s">""</span>, <span class="pl-s">"{%m:%m}\n"</span>, <span class="pl-en">MG_ESC</span>(<span class="pl-s">"error"</span>), <span class="pl-en">MG_ESC</span>(<span class="pl-s">"Unsupported URI"</span>)); 
    }
  }
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="static void fn(struct mg_connection *c, int ev, void *ev_data) {
  if (ev == MG_EV_HTTP_MSG) {
    struct mg_http_message *hm = (struct mg_http_message *) ev_data;
    if (mg_http_match_uri(hm, &quot;/api/time/get&quot;)) {
      mg_http_reply(c, 200, &quot;&quot;, &quot;{%m:%lu}\n&quot;, MG_ESC(&quot;time&quot;), time(NULL));
    } else {
      mg_http_reply(c, 500, &quot;&quot;, &quot;{%m:%m}\n&quot;, MG_ESC(&quot;error&quot;), MG_ESC(&quot;Unsupported URI&quot;)); 
    }
  }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">订阅主题</font></font><code>aa/bb</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并打印所有传入消息的 MQTT 客户端：</font></font></p>
<div class="highlight highlight-source-c notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">static</span> <span class="pl-smi">void</span> <span class="pl-en">fn</span>(<span class="pl-k">struct</span> <span class="pl-smi">mg_connection</span> <span class="pl-c1">*</span><span class="pl-s1">c</span>, <span class="pl-smi">int</span> <span class="pl-s1">ev</span>, <span class="pl-smi">void</span> <span class="pl-c1">*</span><span class="pl-s1">ev_data</span>) {
  <span class="pl-k">if</span> (<span class="pl-s1">ev</span> <span class="pl-c1">==</span> <span class="pl-c1">MG_EV_MQTT_OPEN</span>) {
    <span class="pl-k">struct</span> <span class="pl-smi">mg_mqtt_opts</span> <span class="pl-s1">opts</span> <span class="pl-c1">=</span> {.<span class="pl-c1">qos</span> <span class="pl-c1">=</span> <span class="pl-c1">1</span>, .<span class="pl-c1">topic</span> <span class="pl-c1">=</span> <span class="pl-en">mg_str</span>(<span class="pl-s">"aa/bb"</span>)};
    <span class="pl-en">mg_mqtt_sub</span>(<span class="pl-s1">c</span>, <span class="pl-c1">&amp;</span><span class="pl-s1">opts</span>);
  } <span class="pl-k">else</span> <span class="pl-k">if</span> (<span class="pl-s1">ev</span> <span class="pl-c1">==</span> <span class="pl-c1">MG_EV_MQTT_MSG</span>) {
    <span class="pl-k">struct</span> <span class="pl-smi">mg_mqtt_message</span> <span class="pl-c1">*</span><span class="pl-s1">mm</span> <span class="pl-c1">=</span> (<span class="pl-k">struct</span> <span class="pl-smi">mg_mqtt_message</span> <span class="pl-c1">*</span>) <span class="pl-s1">ev_data</span>;
    <span class="pl-en">printf</span>(<span class="pl-s">"Topic: %.*s, Message: %.*s"</span>,
           <span class="pl-s1">mm</span><span class="pl-c1">-&gt;</span><span class="pl-c1">topic</span>.<span class="pl-c1">len</span>, <span class="pl-s1">mm</span><span class="pl-c1">-&gt;</span><span class="pl-c1">topic</span>.<span class="pl-c1">ptr</span>,
           <span class="pl-s1">mm</span><span class="pl-c1">-&gt;</span><span class="pl-c1">data</span>.<span class="pl-c1">len</span>, <span class="pl-s1">mm</span><span class="pl-c1">-&gt;</span><span class="pl-c1">data</span>.<span class="pl-c1">ptr</span>);
  }
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="static void fn(struct mg_connection *c, int ev, void *ev_data) {
  if (ev == MG_EV_MQTT_OPEN) {
    struct mg_mqtt_opts opts = {.qos = 1, .topic = mg_str(&quot;aa/bb&quot;)};
    mg_mqtt_sub(c, &amp;opts);
  } else if (ev == MG_EV_MQTT_MSG) {
    struct mg_mqtt_message *mm = (struct mg_mqtt_message *) ev_data;
    printf(&quot;Topic: %.*s, Message: %.*s&quot;,
           mm->topic.len, mm->topic.ptr,
           mm->data.len, mm->data.ptr);
  }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-commercial-use" class="anchor" aria-hidden="true" tabindex="-1" href="#commercial-use"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">商业用途</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mongoose 被数百家企业使用，从西门子、施耐德电气、博通、博世、谷歌、三星、高通、卡特彼勒等财富 500 强巨头到小型企业</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于解决广泛的业务需求，例如在设备上实现Web UI界面、RESTful API服务、遥测数据交换、产品远程控制、远程软件更新、远程监控等</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署到全球生产环境中的数亿台设备</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看</font><a href="https://mongoose.ws/case-studies/schneider-electric/" rel="nofollow"><font style="vertical-align: inherit;">施耐德电气</font></a><font style="vertical-align: inherit;">（工业自动化）、</font><a href="https://mongoose.ws/case-studies/broadcom/" rel="nofollow"><font style="vertical-align: inherit;">Broadcom</font></a><font style="vertical-align: inherit;">（半导体）、</font><a href="https://mongoose.ws/case-studies/pilz/" rel="nofollow"><font style="vertical-align: inherit;">Pilz</font></a><font style="vertical-align: inherit;">（工业自动化）等</font><font style="vertical-align: inherit;">尊贵客户的</font></font><a href="https://mongoose.ws/case-studies/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">案例研究</font></font></a><font style="vertical-align: inherit;"></font><a href="https://mongoose.ws/case-studies/schneider-electric/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://mongoose.ws/case-studies/broadcom/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://mongoose.ws/case-studies/pilz/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看</font><font style="vertical-align: inherit;">将 Mongoose 集成到其商业产品中的工程师的</font></font><a href="https://mongoose.ws/testimonials/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推荐</font></font></a><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们提供</font></font><a href="https://mongoose.ws/licensing/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评估和商业许可</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://mongoose.ws/support/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、咨询和</font></font><a href="https://mongoose.ws/integration/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集成服务</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 请随时</font></font><a href="https://mongoose.ws/contact/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联系我们</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-security" class="anchor" aria-hidden="true" tabindex="-1" href="#security"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们认真对待安全：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mongoose 存储库运行
</font></font><a href="https://github.com/cesanta/mongoose/actions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由 GitHub 支持的持续集成测试</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，该测试在每次提交到存储库时都会运行数百个单元测试。</font><font style="vertical-align: inherit;">我们的</font></font><a href="https://github.com/cesanta/mongoose/tree/master/test"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单元测试</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
采用现代地址清理技术构建，有助于及早发现安全漏洞</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mongoose 存储库已集成到 Google 的
</font></font><a href="https://bugs.chromium.org/p/oss-fuzz/issues/list?sort=-opened&amp;can=1&amp;q=proj:mongoose" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">oss-fuzz 连续模糊器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中
，可连续扫描潜在漏洞</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们定期收到来自独立安全组织（例如
</font></font><a href="https://www.cisco.com/c/en/us/products/security/talos.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cisco Talos</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
 </font></font><a href="https://www.microsoft.com/en-us/msrc" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Microsoft 安全响应中心</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
 </font></font><a href="https://www.mitre.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MITRE Corporation</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
 </font></font><a href="https://www.compass-security.com/en/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Compass Security</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等）的漏洞报告。</font><font style="vertical-align: inherit;">如果发现漏洞，我们将根据行业最佳实践采取行动：保留该出版物，修复软件并通知所有拥有适当订阅的客户</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的一些客户（例如 NASA）有特定的安全要求并运行独立的安全审核，我们会收到通知，如果出现任何问题，请采取与 (3) 类似的操作。</font></font></li>
</ol>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributions" class="anchor" aria-hidden="true" tabindex="-1" href="#contributions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎贡献！</font><font style="vertical-align: inherit;">请遵循以下准则：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">签署</font></font><a href="https://cesanta.com/cla.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cesanta CLA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并发送 GitHub 拉取请求</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保 PR 只有一次提交，并且只处理一个问题</font></font></li>
</ul>
</article></div>
