# ydata-profiling

[![Build Status](https://github.com/ydataai/pandas-profiling/actions/workflows/tests.yml/badge.svg?branch=master)](https://github.com/ydataai/pandas-profiling/actions/workflows/tests.yml)
[![PyPI download month](https://img.shields.io/pypi/dm/ydata-profiling.svg)](https://pypi.python.org/pypi/ydata-profiling/)
[![](https://pepy.tech/badge/pandas-profiling)](https://pypi.org/project/ydata-profiling/)
[![Code Coverage](https://codecov.io/gh/ydataai/pandas-profiling/branch/master/graph/badge.svg?token=gMptB4YUnF)](https://codecov.io/gh/ydataai/pandas-profiling)
[![Release Version](https://img.shields.io/github/release/ydataai/pandas-profiling.svg)](https://github.com/ydataai/pandas-profiling/releases)
[![Python Version](https://img.shields.io/pypi/pyversions/ydata-profiling)](https://pypi.org/project/ydata-profiling/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)

<p align="center"><img width="300" src="https://assets.ydata.ai/oss/ydata-profiling_black.png" alt="YData Profiling Logo"></p>

<p align="center">
  <a href="https://ydata-profiling.ydata.ai/docs/master/">Documentation</a>
  |
  <a href="https://tiny.ydata.ai/dcai-ydata-profiling">Discord</a>
  | 
  <a href="https://stackoverflow.com/questions/tagged/pandas-profiling+or+ydata-profiling">Stack Overflow</a>
  |
  <a href="https://ydata-profiling.ydata.ai/docs/master/pages/reference/changelog.html#changelog">Latest changelog</a>

</p>


<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-ydata-profiling" class="anchor" aria-hidden="true" tabindex="-1" href="#ydata-profiling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ydata-分析</font></font></h1>
<p dir="auto"><a href="https://github.com/ydataai/pandas-profiling/actions/workflows/tests.yml"><img src="https://github.com/ydataai/pandas-profiling/actions/workflows/tests.yml/badge.svg?branch=master" alt="构建状态" style="max-width: 100%;"></a>
<a href="https://pypi.python.org/pypi/ydata-profiling/" rel="nofollow"><img src="https://camo.githubusercontent.com/6f86a39abd700ccce51b3a20e630b47e92133b4e0f87864b134104c086d1f202/68747470733a2f2f696d672e736869656c64732e696f2f707970692f646d2f79646174612d70726f66696c696e672e737667" alt="PyPI 下载月" data-canonical-src="https://img.shields.io/pypi/dm/ydata-profiling.svg" style="max-width: 100%;"></a>
<a href="https://pypi.org/project/ydata-profiling/" rel="nofollow"><img src="https://camo.githubusercontent.com/eb218095388b5b5e384623d29a7023aaca2a064cc2940e1e25f869b9df6accb1/68747470733a2f2f706570792e746563682f62616467652f70616e6461732d70726f66696c696e67" alt="" data-canonical-src="https://pepy.tech/badge/pandas-profiling" style="max-width: 100%;"></a>
<a href="https://codecov.io/gh/ydataai/pandas-profiling" rel="nofollow"><img src="https://camo.githubusercontent.com/c6c09793aa072eebe1c551be5aefb8e25a2ea435df9990607556fae662d01f9a/68747470733a2f2f636f6465636f762e696f2f67682f796461746161692f70616e6461732d70726f66696c696e672f6272616e63682f6d61737465722f67726170682f62616467652e7376673f746f6b656e3d674d7074423459556e46" alt="代码覆盖率" data-canonical-src="https://codecov.io/gh/ydataai/pandas-profiling/branch/master/graph/badge.svg?token=gMptB4YUnF" style="max-width: 100%;"></a>
<a href="https://github.com/ydataai/pandas-profiling/releases"><img src="https://camo.githubusercontent.com/ddf777a43f749546ab257046e319a4e1d4f905f6013c26fac832525e8d6c1c7f/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f796461746161692f70616e6461732d70726f66696c696e672e737667" alt="发布版本" data-canonical-src="https://img.shields.io/github/release/ydataai/pandas-profiling.svg" style="max-width: 100%;"></a>
<a href="https://pypi.org/project/ydata-profiling/" rel="nofollow"><img src="https://camo.githubusercontent.com/5616740308dc06cc6d6d4c38d33adf2cae7e7eb755b870e49cee426a6da06440/68747470733a2f2f696d672e736869656c64732e696f2f707970692f707976657273696f6e732f79646174612d70726f66696c696e67" alt="Python版本" data-canonical-src="https://img.shields.io/pypi/pyversions/ydata-profiling" style="max-width: 100%;"></a>
<a href="https://github.com/python/black"><img src="https://camo.githubusercontent.com/7d770c433d6198d89f8c1e2f187b904a9721d176259d0e97157337741cc8e837/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636f64652532307374796c652d626c61636b2d3030303030302e737667" alt="代码风格：黑色" data-canonical-src="https://img.shields.io/badge/code%20style-black-000000.svg" style="max-width: 100%;"></a></p>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/2a859e96cdec98998f2e5aa4c58bed85f2db22ceed2362486aa93ec596c7226b/68747470733a2f2f6173736574732e79646174612e61692f6f73732f79646174612d70726f66696c696e675f626c61636b2e706e67"><img width="300" src="https://camo.githubusercontent.com/2a859e96cdec98998f2e5aa4c58bed85f2db22ceed2362486aa93ec596c7226b/68747470733a2f2f6173736574732e79646174612e61692f6f73732f79646174612d70726f66696c696e675f626c61636b2e706e67" alt="YData 分析徽标" data-canonical-src="https://assets.ydata.ai/oss/ydata-profiling_black.png" style="max-width: 100%;"></a></p>
<p align="center" dir="auto">
  <a href="https://ydata-profiling.ydata.ai/docs/master/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
  |
  </font></font><a href="https://tiny.ydata.ai/dcai-ydata-profiling" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不和谐</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
  | 
  </font></font><a href="https://stackoverflow.com/questions/tagged/pandas-profiling+or+ydata-profiling" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">堆栈溢出</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
  |
  </font></font><a href="https://ydata-profiling.ydata.ai/docs/master/pages/reference/changelog.html#changelog" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最新变更日志</font></font></a>
</p>
<p align="center" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
  你喜欢这个项目吗？</font><font style="vertical-align: inherit;">向我们展示您的爱并</font></font><a href="https://engage.ydata.ai" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供反馈！</font></font></a>
</p>
<p dir="auto"><code>ydata-profiling</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要目标是通过一致且快速的解决方案提供单行探索性数据分析 (EDA) 体验。</font><font style="vertical-align: inherit;">与 pandas 函数一样，ydata-profiling 非常方便，它提供了 DataFrame 的扩展分析，同时允许以不同的格式（例如</font><strong><font style="vertical-align: inherit;">html</font></strong><font style="vertical-align: inherit;">和</font><strong><font style="vertical-align: inherit;">json ）</font></strong></font><code>df.describe()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">导出数据分析</font><font style="vertical-align: inherit;">。</font></font><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该包输出数据集的简单且经过消化的分析，包括</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时间序列</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正在寻找可以与您的数据库系统完全集成的可扩展解决方案？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
利用 YData Fabric 数据目录连接到不同的数据库和存储（Oracle、snowflake、PostGreSQL、GCS、S3 等），并利用 Fabric 中的交互式和引导式分析体验。</font><font style="vertical-align: inherit;">查看</font></font><a href="http://ydata.ai/register?utm_source=ydata-profiling&amp;utm_medium=documentation&amp;utm_campaign=YData%20Fabric%20Community" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区版本</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<h2 tabindex="-1" dir="auto"><a id="user-content-️-quickstart" class="anchor" aria-hidden="true" tabindex="-1" href="#️-quickstart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><g-emoji class="g-emoji" alias="arrow_forward"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">▶️</font></font></g-emoji><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-install" class="anchor" aria-hidden="true" tabindex="-1" href="#install"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h3>
<div class="highlight highlight-source-batchfile notranslate position-relative overflow-auto" dir="auto"><pre>pip install ydata-profiling</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install ydata-profiling" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者</font></font></p>
<div class="highlight highlight-source-batchfile notranslate position-relative overflow-auto" dir="auto"><pre>conda install -c conda-forge ydata-profiling</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="conda install -c conda-forge ydata-profiling" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-start-profiling" class="anchor" aria-hidden="true" tabindex="-1" href="#start-profiling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始分析</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>DataFrame</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先像平常一样</font><font style="vertical-align: inherit;">加载 pandas ，例如使用：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">numpy</span> <span class="pl-k">as</span> <span class="pl-s1">np</span>
<span class="pl-k">import</span> <span class="pl-s1">pandas</span> <span class="pl-k">as</span> <span class="pl-s1">pd</span>
<span class="pl-k">from</span> <span class="pl-s1">ydata_profiling</span> <span class="pl-k">import</span> <span class="pl-v">ProfileReport</span>

<span class="pl-s1">df</span> <span class="pl-c1">=</span> <span class="pl-s1">pd</span>.<span class="pl-v">DataFrame</span>(<span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">rand</span>(<span class="pl-c1">100</span>, <span class="pl-c1">5</span>), <span class="pl-s1">columns</span><span class="pl-c1">=</span>[<span class="pl-s">"a"</span>, <span class="pl-s">"b"</span>, <span class="pl-s">"c"</span>, <span class="pl-s">"d"</span>, <span class="pl-s">"e"</span>])</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import numpy as np
import pandas as pd
from ydata_profiling import ProfileReport

df = pd.DataFrame(np.random.rand(100, 5), columns=[&quot;a&quot;, &quot;b&quot;, &quot;c&quot;, &quot;d&quot;, &quot;e&quot;])" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要生成标准分析报告，只需运行：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">profile</span> <span class="pl-c1">=</span> <span class="pl-v">ProfileReport</span>(<span class="pl-s1">df</span>, <span class="pl-s1">title</span><span class="pl-c1">=</span><span class="pl-s">"Profiling Report"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="profile = ProfileReport(df, title=&quot;Profiling Report&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content--key-features" class="anchor" aria-hidden="true" tabindex="-1" href="#-key-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📊 主要特点</font></font></h2>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型推断</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：自动检测列的数据类型（</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分类</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数字</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日期</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等）</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：您可能需要处理的数据中的问题/挑战的摘要（</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">丢失数据</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不准确</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">偏斜</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等）</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单变量分析</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：包括描述性统计（平均值、中位数、众数等）和信息可视化，例如分布直方图</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多变量分析</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：包括相关性、缺失数据、重复行的详细分析以及变量成对交互的可视化支持</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时间序列</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：包括与时间相关数据相关的不同统计信息，例如自相关和季节性，沿着 ACF 和 PACF 图。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本分析</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：最常见的类别（大写、小写、分隔符）、脚本（拉丁文、西里尔文）和块（ASCII、西里尔文）</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件和图像分析</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：文件大小、创建日期、尺寸、截断图像的指示以及 EXIF 元数据的存在</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比较数据集</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：单行解决方案可快速生成有关数据集比较的完整报告</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">灵活的输出格式</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：所有分析都可以导出为 HTML 报告，可以轻松地与不同方共享，作为 JSON 可以轻松集成到自动化系统中，也可以作为 Jupyter Notebook 中的小部件导出。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该报告还包含三个附加部分：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概述</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：主要是有关数据集的全局详细信息（记录数、变量数、整体缺失和重复、内存占用）</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：潜在数据质量问题的全面自动列表（高相关性、偏度、均匀性、零值、缺失值、常量值等）</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重现</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：有关分析的技术细节（时间、版本和配置）</font></font></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content--latest-features" class="anchor" aria-hidden="true" tabindex="-1" href="#-latest-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🎁 最新功能</font></font></h3>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">想要扩大规模吗？</font></font><a href="https://ydata-profiling.ydata.ai/docs/master/pages/integrations/pypspark.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过 ⭐⚡ Spark 支持</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看最新版本</font><font style="vertical-align: inherit;">！</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正在寻找如何对时间序列进行 EDA 🕛 ？</font><font style="vertical-align: inherit;">检查</font></font><a href="https://towardsdatascience.com/how-to-do-an-eda-for-time-series-cbb92b3b1913" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这篇博文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您想比较 2 个数据集并获得报告吗？</font><font style="vertical-align: inherit;">检查</font></font><a href="https://medium.com/towards-artificial-intelligence/how-to-compare-2-dataset-with-pandas-profiling-2ae3a9d7695e" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这篇博文</font></font></a></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content--spark" class="anchor" aria-hidden="true" tabindex="-1" href="#-spark"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✨ 火花</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spark 支持已经发布，但我们一直在寻找额外的帮助👐。
</font></font><a href="https://github.com/ydataai/ydata-profiling/projects/3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查当前正在进行的工作！</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--use-cases" class="anchor" aria-hidden="true" tabindex="-1" href="#-use-cases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📝 使用案例</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YData-profiling 可用于提供各种不同的用例。</font><font style="vertical-align: inherit;">该文档包括解决这些问题的指南、提示和技巧：</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用案例</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://docs.profiling.ydata.ai/latest/features/comparing_datasets" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比较数据集</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比较同一数据集的多个版本</font></font></td>
</tr>
<tr>
<td><a href="https://docs.profiling.ydata.ai/latest/features/time_series_datasets" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分析时间序列数据集</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用一行代码生成时间序列数据集的报告</font></font></td>
</tr>
<tr>
<td><a href="https://docs.profiling.ydata.ai/latest/features/big_data" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分析大型数据集</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关如何准备数据和配置</font></font><code>ydata-profiling</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以处理大型数据集的提示</font></font></td>
</tr>
<tr>
<td><a href="https://docs.profiling.ydata.ai/latest/features/sensitive_data" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">处理敏感数据</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成注意输入数据集中敏感数据的报告</font></font></td>
</tr>
<tr>
<td><a href="https://docs.profiling.ydata.ai/latest/features/metadata" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据集元数据和数据字典</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用数据集详细信息和特定于列的数据字典补充报告</font></font></td>
</tr>
<tr>
<td><a href="https://docs.profiling.ydata.ai/latest/features/custom_reports" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义报告的外观</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更改报表页面和所包含可视化效果的外观</font></font></td>
</tr>
<tr>
<td><a href="https://docs.profiling.ydata.ai/latest/features/collaborative_data_profiling" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分析数据库</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要在组织的数据库中获得无缝分析体验，请检查</font></font><a href="https://ydata.ai/products/data_catalog" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fabric Data Catalog</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，它允许使用来自不同类型存储的数据，例如 RDBM（Azure SQL、PostGreSQL、Oracle 等）和对象存储（Google Cloud Storage、AWS S3、雪花等）等。</font></font></td>
</tr>
</tbody>
</table>
<h3 tabindex="-1" dir="auto"><a id="user-content-using-inside-jupyter-notebooks" class="anchor" aria-hidden="true" tabindex="-1" href="#using-inside-jupyter-notebooks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Jupyter Notebooks 内部使用</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jupyter Notebook 中有两个界面可以使用报告：通过小部件和通过嵌入式 HTML 报告。</font></font></p>
<p dir="auto"><animated-image data-catalyst="" style="width: 800px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/dd1a8a7574967f959c87d01569936a21ff5d1dd8bbb3adaf039e050113b9a50d/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f776964676574732e676966" data-target="animated-image.originalLink" hidden=""><img alt="Notebook Widgets" src="https://camo.githubusercontent.com/dd1a8a7574967f959c87d01569936a21ff5d1dd8bbb3adaf039e050113b9a50d/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f776964676574732e676966" data-canonical-src="https://ydata-profiling.ydata.ai/docs/master/assets/widgets.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/dd1a8a7574967f959c87d01569936a21ff5d1dd8bbb3adaf039e050113b9a50d/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f776964676574732e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Notebook Widgets" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/dd1a8a7574967f959c87d01569936a21ff5d1dd8bbb3adaf039e050113b9a50d/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f776964676574732e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open in new window" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/dd1a8a7574967f959c87d01569936a21ff5d1dd8bbb3adaf039e050113b9a50d/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f776964676574732e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上述内容是通过简单地将报告显示为一组小部件来实现的。</font><font style="vertical-align: inherit;">在 Jupyter Notebook 中，运行：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">profile</span>.<span class="pl-en">to_widgets</span>()</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="profile.to_widgets()" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTML 报告可以以类似的方式直接嵌入到单元格中：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">profile</span>.<span class="pl-en">to_notebook_iframe</span>()</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="profile.to_notebook_iframe()" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><animated-image data-catalyst="" style="width: 800px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/b7387317ad9108d25f0275c766783bed404854eb1c57e04027c80513f8819e93/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f696672616d652e676966" data-target="animated-image.originalLink" hidden=""><img alt="HTML" src="https://camo.githubusercontent.com/b7387317ad9108d25f0275c766783bed404854eb1c57e04027c80513f8819e93/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f696672616d652e676966" data-canonical-src="https://ydata-profiling.ydata.ai/docs/master/assets/iframe.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/b7387317ad9108d25f0275c766783bed404854eb1c57e04027c80513f8819e93/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f696672616d652e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="HTML" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/b7387317ad9108d25f0275c766783bed404854eb1c57e04027c80513f8819e93/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f696672616d652e676966">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open in new window" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/b7387317ad9108d25f0275c766783bed404854eb1c57e04027c80513f8819e93/68747470733a2f2f79646174612d70726f66696c696e672e79646174612e61692f646f63732f6d61737465722f6173736574732f696672616d652e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-exporting-the-report-to-a-file" class="anchor" aria-hidden="true" tabindex="-1" href="#exporting-the-report-to-a-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将报告导出到文件</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要生成 HTML 报告文件，请将其保存</font></font><code>ProfileReport</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到对象并使用以下</font></font><code>to_file()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">profile</span>.<span class="pl-en">to_file</span>(<span class="pl-s">"your_report.html"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="profile.to_file(&quot;your_report.html&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，可以以 JSON 文件形式获取报告数据：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"># As a JSON string</span>
<span class="pl-s1">json_data</span> <span class="pl-c1">=</span> <span class="pl-s1">profile</span>.<span class="pl-en">to_json</span>()

<span class="pl-c"># As a file</span>
<span class="pl-s1">profile</span>.<span class="pl-en">to_file</span>(<span class="pl-s">"your_report.json"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# As a JSON string
json_data = profile.to_json()

# As a file
profile.to_file(&quot;your_report.json&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-using-in-the-command-line" class="anchor" aria-hidden="true" tabindex="-1" href="#using-in-the-command-line"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在命令行中使用</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于标准格式的 CSV 文件（可以直接由 pandas 读取，无需额外设置），</font></font><code>ydata_profiling</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以在命令行中使用可执行文件。</font><font style="vertical-align: inherit;">下面的示例</font><font style="vertical-align: inherit;">通过处理数据集，使用</font><font style="vertical-align: inherit;">文件中</font><font style="vertical-align: inherit;">名为 的配置文件生成名为</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Example Profiling Report</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的报告。</font></font><code>default.yaml</code><font style="vertical-align: inherit;"></font><code>report.html</code><font style="vertical-align: inherit;"></font><code>data.csv</code><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>ydata_profiling --title <span class="pl-s"><span class="pl-pds">"</span>Example Profiling Report<span class="pl-pds">"</span></span> --config_file default.yaml data.csv report.html</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ydata_profiling --title &quot;Example Profiling Report&quot; --config_file default.yaml data.csv report.html" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关 CLI 的更多详细信息，请参阅</font></font><a href="https://ydata-profiling.ydata.ai/docs/master/pages/getting_started/quickstart.html#command-line-usage" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--examples" class="anchor" aria-hidden="true" tabindex="-1" href="#-examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">👀 例子</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下示例报告展示了该包在各种数据集和数据类型中的潜力：</font></font></p>
<ul dir="auto">
<li><a href="https://ydata-profiling.ydata.ai/examples/master/census/census_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人口普查收入</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（将收入与其他人口统计特征相关的美国成人人口普查数据）</font></font></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/meteorites/meteorites_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NASA Meteorites</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（陨石着陆的综合集 - 物体属性和位置）</font></font><a href="https://colab.research.google.com/github/ydataai/pandas-profiling/blob/master/examples/meteorites/meteorites_cloud.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" style="max-width: 100%;"></a> <a href="https://mybinder.org/v2/gh/ydataai/pandas-profiling/master?filepath=examples%2Fmeteorites%2Fmeteorites%5Fcloud.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/483bae47a175c24dfbfc57390edd8b6982ac5fb3/68747470733a2f2f6d7962696e6465722e6f72672f62616467655f6c6f676f2e737667" alt="活页夹" style="max-width: 100%;"></a></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/titanic/titanic_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">泰坦尼克号</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（数据集的“Wonderwall”）</font></font><a href="https://colab.research.google.com/github/ydataai/pandas-profiling/blob/master/examples/titanic/titanic_cloud.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" style="max-width: 100%;"></a> <a href="https://mybinder.org/v2/gh/ydataai/pandas-profiling/master?filepath=examples%2Ftitanic%2Ftitanic%5Fcloud.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/483bae47a175c24dfbfc57390edd8b6982ac5fb3/68747470733a2f2f6d7962696e6465722e6f72672f62616467655f6c6f676f2e737667" alt="活页夹" style="max-width: 100%;"></a></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/nza/nza_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NZA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（荷兰医疗保健管理局的开放数据）</font></font></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/stata_auto/stata_auto_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stata Auto</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（1978 年汽车数据）</font></font></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/colors/colors_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">颜色</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（简单的颜色数据集）</font></font></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/vektis/vektis_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Vektis</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（Vektis 荷兰医疗保健数据）</font></font></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/bank_marketing_data/uci_bank_marketing_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">UCI 银行数据集</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（来自银行的营销数据集）</font></font></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/features/russian_vocabulary.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">俄语词汇</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（100 个最常见的俄语单词，展示 unicode 文本分析）</font></font></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/features/website_inaccessibility_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网站不可访问性</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（网站可访问性分析，展示对 URL 数据的支持）</font></font></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/features/united_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">橙子价格</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font></li>
<li><a href="https://ydata-profiling.ydata.ai/examples/master/features/flatly_report.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">煤炭价格</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（简单的定价演变数据集，展示主题选项）</font></font></li>
<li><a href="https://github.com/ydataai/pandas-profiling/tree/master/examples/usaairquality"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">美国空气质量</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（时间序列空气质量数据集 EDA 示例）</font></font></li>
<li><a href="https://github.com/ydataai/pandas-profiling/tree/master/examples/hcc"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HCC</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（来自医疗保健的开放数据集，展示预处理前后两组数据之间的比较）</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-️-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#️-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🛠️安装</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他详细信息（包括有关小部件支持的信息）可</font></font><a href="https://ydata-profiling.ydata.ai/docs/master/pages/getting_started/installation.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在文档中</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-using-pip" class="anchor" aria-hidden="true" tabindex="-1" href="#using-pip"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用点</font></font></h3>
<p dir="auto"><a href="https://pepy.tech/project/ydata-profiling" rel="nofollow"><img src="https://camo.githubusercontent.com/dc53e3b09c7b35700f16f88da0fe7a16efc6e49302d3cc08a8a2eedcfb6dfd3b/68747470733a2f2f706570792e746563682f62616467652f79646174612d70726f66696c696e67" alt="PyPi 下载" data-canonical-src="https://pepy.tech/badge/ydata-profiling" style="max-width: 100%;"></a>
<a href="https://pepy.tech/project/ydata-profiling/month" rel="nofollow"><img src="https://camo.githubusercontent.com/a8f7c70fdb4ad6774416a82cb2651489ff2be7e8fc5ca9eb2b4ffe0ec0ce930c/68747470733a2f2f706570792e746563682f62616467652f70616e6461732d70726f66696c696e672f6d6f6e7468" alt="PyPi 每月下载量" data-canonical-src="https://pepy.tech/badge/pandas-profiling/month" style="max-width: 100%;"></a>
<a href="https://pypi.org/project/ydata-profiling/" rel="nofollow"><img src="https://camo.githubusercontent.com/11f6ecc1b9ded61927615b086b5e4845613579145aa96a8f86af163cf78650ee/68747470733a2f2f62616467652e667572792e696f2f70792f79646174612d70726f66696c696e672e737667" alt="PyPi版本" data-canonical-src="https://badge.fury.io/py/ydata-profiling.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以</font></font><code>pip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过运行以下命令使用包管理器进行安装：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install -U ydata-profiling</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install -U ydata-profiling" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-extras" class="anchor" aria-hidden="true" tabindex="-1" href="#extras"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附加功能</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该包声明了“extras”，即附加依赖项集。</font></font></p>
<ul dir="auto">
<li><code>[notebook]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：支持在 Jupyter 笔记本小部件中渲染报告。</font></font></li>
<li><code>[unicode]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：支持更详细的 Unicode 分析，但代价是额外的磁盘空间。</font></font></li>
<li><code>[pyspark]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：支持pyspark进行大数据集分析</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装这些，例如</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install -U ydata-profiling[notebook,unicode,pyspark]</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install -U ydata-profiling[notebook,unicode,pyspark]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-using-conda" class="anchor" aria-hidden="true" tabindex="-1" href="#using-conda"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用康达</font></font></h3>
<p dir="auto"><a href="https://anaconda.org/conda-forge/pandas-profiling" rel="nofollow"><img src="https://camo.githubusercontent.com/dd9bb66ddef827050412f5dd78ccbb7a8cb5bfe4d62f9a084520a1b4bbd765a1/68747470733a2f2f696d672e736869656c64732e696f2f636f6e64612f646e2f636f6e64612d666f7267652f70616e6461732d70726f66696c696e672e737667" alt="康达下载" data-canonical-src="https://img.shields.io/conda/dn/conda-forge/pandas-profiling.svg" style="max-width: 100%;"></a>
<a href="https://anaconda.org/conda-forge/pandas-profiling" rel="nofollow"><img src="https://camo.githubusercontent.com/be8289861d10b61f9203ae60974fd8a3cbdf5507e03570f5cc83df34aafa4b0f/68747470733a2f2f696d672e736869656c64732e696f2f636f6e64612f766e2f636f6e64612d666f7267652f70616e6461732d70726f66696c696e672e737667" alt="康达版本" data-canonical-src="https://img.shields.io/conda/vn/conda-forge/pandas-profiling.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以</font></font><code>conda</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过运行以下命令使用包管理器进行安装：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>conda install -c conda-forge ydata-profiling</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="conda install -c conda-forge ydata-profiling" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-from-source-development" class="anchor" aria-hidden="true" tabindex="-1" href="#from-source-development"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源头（开发）</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过克隆存储库来下载源代码，或单击</font></font><a href="https://github.com/ydataai/pandas-profiling/archive/master.zip"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“下载 ZIP”</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载最新的稳定版本。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过导航到正确的目录并运行来安装它：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install -e <span class="pl-c1">.</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install -e ." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分析报告是用 HTML 和 CSS 编写的，这意味着需要现代浏览器。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您需要</font></font><a href="https://python3statement.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 3</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来运行该包。</font><font style="vertical-align: inherit;">其他依赖项可以在需求文件中找到：</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件名</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://github.com/ydataai/pandas-profiling/blob/master/requirements.txt"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求.txt</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包装要求</font></font></td>
</tr>
<tr>
<td><a href="https://github.com/ydataai/pandas-profiling/blob/master/requirements-dev.txt"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需求-dev.txt</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发展要求</font></font></td>
</tr>
<tr>
<td><a href="https://github.com/ydataai/pandas-profiling/blob/master/requirements-test.txt"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需求测试.txt</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试要求</font></font></td>
</tr>
<tr>
<td><a href="https://github.com/ydataai/pandas-profiling/blob/master/setup.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装程序.py</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">小部件等的要求</font></font></td>
</tr>
</tbody>
</table>
<h2 tabindex="-1" dir="auto"><a id="user-content--integrations" class="anchor" aria-hidden="true" tabindex="-1" href="#-integrations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔗 集成</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了最大限度地提高其在现实世界中的实用性，</font></font><code>ydata-profiling</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与数据科学生态系统中的各种其他参与者进行了一系列隐式和显式集成：</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一体化型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://docs.profiling.ydata.ai/latest/integrations/other_dataframe_libraries" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他 DataFrame 库</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何计算存储在 pandas 以外的库中的数据的分析</font></font></td>
</tr>
<tr>
<td><a href="https://ydata-profiling.ydata.ai/docs/master/pages/integrations/great_expectations.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远大的期望</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直接从分析报告中</font><font style="vertical-align: inherit;">生成</font></font><a href="https://greatexpectations.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远大期望期望套件</font></font></a><font style="vertical-align: inherit;"></font></td>
</tr>
<tr>
<td><a href="https://docs.profiling.ydata.ai/latest/integrations/interactive_applications" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">互动应用</font></font></a></td>
<td><font style="vertical-align: inherit;"></font><a href="http://streamlit.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在Streamlit</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="http://dash.plotly.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dash</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="https://panel.holoviz.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Panel</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序</font><font style="vertical-align: inherit;">中嵌入分析报告</font></font></td>
</tr>
<tr>
<td><a href="https://ydata-profiling.ydata.ai/docs/master/pages/integrations/pipelines.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管道</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与</font></font><a href="https://airflow.apache.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Airflow</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="https://kedro.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kedro等 DAG 工作流执行工具集成</font></font></a></td>
</tr>
<tr>
<td><a href="https://ydata-profiling.ydata.ai/docs/master/pages/integrations/cloud_services.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">云服务</font></font></a></td>
<td><font style="vertical-align: inherit;"><a href="https://lambdalabs.com" rel="nofollow"><font style="vertical-align: inherit;">在Lambda</font></a><font style="vertical-align: inherit;">、</font><a href="https://github.com/GoogleCloudPlatform/analytics-componentized-patterns/blob/master/retail/propensity-model/bqml/bqml_kfp_retail_propensity_to_purchase.ipynb"><font style="vertical-align: inherit;">Google Cloud</font></a><font style="vertical-align: inherit;">或</font><a href="https://www.kaggle.com/code" rel="nofollow"><font style="vertical-align: inherit;">Kaggle</font></a></font><code>ydata-profiling</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等托管计算服务中</font><font style="vertical-align: inherit;">使用</font></font><a href="https://lambdalabs.com" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/GoogleCloudPlatform/analytics-componentized-patterns/blob/master/retail/propensity-model/bqml/bqml_kfp_retail_propensity_to_purchase.ipynb"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://www.kaggle.com/code" rel="nofollow"><font style="vertical-align: inherit;"></font></a></td>
</tr>
<tr>
<td><a href="https://ydata-profiling.ydata.ai/docs/master/pages/integrations/ides.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IDE</font></font></a></td>
<td><font style="vertical-align: inherit;"><a href="https://www.jetbrains.com/pycharm/" rel="nofollow"><font style="vertical-align: inherit;">直接从PyCharm</font></a></font><code>ydata-profiling</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等集成开发环境</font><font style="vertical-align: inherit;">使用</font></font><a href="https://www.jetbrains.com/pycharm/" rel="nofollow"><font style="vertical-align: inherit;"></font></a></td>
</tr>
</tbody>
</table>
<h2 tabindex="-1" dir="auto"><a id="user-content--support" class="anchor" aria-hidden="true" tabindex="-1" href="#-support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🙋 支持</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要帮忙？</font><font style="vertical-align: inherit;">想分享一个观点吗？</font><font style="vertical-align: inherit;">报告错误？</font><font style="vertical-align: inherit;">合作的想法？</font><font style="vertical-align: inherit;">通过以下渠道联系：</font></font></p>
<ul dir="auto">
<li><a href="https://stackoverflow.com/questions/tagged/pandas-profiling+or+ydata-profiling" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stack Overflow</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：非常适合询问如何使用该包的问题</font></font></li>
<li><a href="https://github.com/ydataai/ydata-profiling/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 问题</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：错误、更改建议、功能请求</font></font></li>
<li><a href="https://tiny.ydata.ai/dcai-ydata-profiling" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Discord</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：非常适合项目讨论、提问、协作、一般聊天</font></font></li>
</ul>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要帮忙？</font></font></strong><font style="vertical-align: inherit;"><a href="https://meetings.hubspot.com/fabiana-clemente" rel="nofollow"><font style="vertical-align: inherit;">通过预订 Pawsome 聊天</font></a></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
，让产品负责人解答您的问题</font><font style="vertical-align: inherit;">！</font><font style="vertical-align: inherit;">🐼</font></font><a href="https://meetings.hubspot.com/fabiana-clemente" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
</blockquote>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">❗ 在 GitHub 上报告问题之前，请查看</font></font><a href="https://docs.profiling.ydata.ai/latest/support-contribution/common_issues" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见问题</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<h2 tabindex="-1" dir="auto"><a id="user-content--contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#-contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤝🏽 贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解如何参与</font></font><a href="https://ydata-profiling.ydata.ai/docs/master/pages/support_contrib/contribution_guidelines.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://tiny.ydata.ai/dcai-ydata-profiling" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以数据为中心的 AI 社区的 Discord</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个提出问题或开始贡献的低门槛场所</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非常感谢我们所有出色的贡献者！</font></font></p>
<a href="https://github.com/ydataai/ydata-profiling/graphs/contributors">
  <img src="https://camo.githubusercontent.com/b1c9e4e86a7a179aa76b6e7b7c84369156c9c2725db8bda4cd72db1056905c26/68747470733a2f2f636f6e747269622e726f636b732f696d6167653f7265706f3d796461746161692f79646174612d70726f66696c696e67" data-canonical-src="https://contrib.rocks/image?repo=ydataai/ydata-profiling" style="max-width: 100%;">
</a>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用</font></font><a href="https://contrib.rocks" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">contrib.rocks</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">制作的贡献者墙。</font></font></p>
</article></div>
