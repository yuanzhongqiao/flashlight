<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://app.circleci.com/pipelines/github/flashlight/flashlight" rel="nofollow"><img src="https://camo.githubusercontent.com/2f9fbbae1539f0a6327fc5f172315f2aa6a6c7e1522d2263487f138d6b9029fb/68747470733a2f2f636972636c6563692e636f6d2f67682f666c6173686c696768742f666c6173686c696768742e7376673f7374796c653d736869656c64" alt="循环CI" data-canonical-src="https://circleci.com/gh/flashlight/flashlight.svg?style=shield" style="max-width: 100%;"></a>
<a href="https://fl.readthedocs.io/en/latest/" rel="nofollow"><img src="https://camo.githubusercontent.com/503c2955fd283cdd691601a4596adfe12d420a0d673e1013a4449096df4577e3/68747470733a2f2f696d672e736869656c64732e696f2f72656164746865646f63732f666c2e737667" alt="文件状态" data-canonical-src="https://img.shields.io/readthedocs/fl.svg" style="max-width: 100%;"></a>
<a href="https://hub.docker.com/r/flml/flashlight/tags" rel="nofollow"><img src="https://camo.githubusercontent.com/c3aff1ff5b0f81de20d44da975984c76d2d29d3ce2ac0c88581dec7133fd79d6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f776f726b666c6f772f7374617475732f666c6173686c696768742f666c6173686c696768742f5075626c697368253230446f636b6572253230696d616765733f6c6162656c3d646f636b6572253230696d6167652532306275696c64" alt="Docker 镜像构建状态" data-canonical-src="https://img.shields.io/github/workflow/status/flashlight/flashlight/Publish%20Docker%20images?label=docker%20image%20build" style="max-width: 100%;"></a>
<a href="https://gitter.im/flashlight-ml/community?utm_source=badge&amp;utm_medium=badge&amp;utm_campaign=pr-badge&amp;utm_content=badge" rel="nofollow"><img src="https://camo.githubusercontent.com/db6665f9d82518efd6db0285540d8493ffdbfad701f71fcbf25869aa0dc7a6b3/68747470733a2f2f696d672e736869656c64732e696f2f6769747465722f726f6f6d2f666c6173686c696768742d6d6c2f636f6d6d756e697479" alt="加入聊天：https://gitter.im/flashlight-ml/community" data-canonical-src="https://img.shields.io/gitter/room/flashlight-ml/community" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://codecov.io/gh/flashlight/flashlight" rel="nofollow"><img src="https://camo.githubusercontent.com/72137a63f489877833a8ba64fc86e994a6b169293cd4d3ba7f4440edd4160f5d/68747470733a2f2f636f6465636f762e696f2f67682f666c6173686c696768742f666c6173686c696768742f6272616e63682f6d61737465722f67726170682f62616467652e7376673f746f6b656e3d7242703441696c4d6330" alt="代码科夫" data-canonical-src="https://codecov.io/gh/flashlight/flashlight/branch/master/graph/badge.svg?token=rBp4AilMc0" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://hub.docker.com/r/flml/flashlight/tags?page=1&amp;ordering=last_updated&amp;name=cuda-latest" rel="nofollow"><img src="https://camo.githubusercontent.com/15a93ce8ee793d38c7458d222ae788b55cd5a4ca606b4596f0699348f3e77af6/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f696d6167652d73697a652f666c6d6c2f666c6173686c696768742f637564612d6c61746573743f6c6162656c3d646f636b657225323025323863756461253239266c6f676f3d646f636b6572" alt="CUDA 后端的 Docker 镜像" data-canonical-src="https://img.shields.io/docker/image-size/flml/flashlight/cuda-latest?label=docker%20%28cuda%29&amp;logo=docker" style="max-width: 100%;"></a>
<a href="https://hub.docker.com/r/flml/flashlight/tags?page=1&amp;ordering=last_updated&amp;name=cpu-latest" rel="nofollow"><img src="https://camo.githubusercontent.com/f81f17f44353e258f35f514515b7e76617ce730e4a1700d792422756106022f3/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f696d6167652d73697a652f666c6d6c2f666c6173686c696768742f6370752d6c61746573743f6c6162656c3d646f636b6572253230253238637075253239266c6f676f3d646f636b6572" alt="CPU 后端的 Docker 镜像" data-canonical-src="https://img.shields.io/docker/image-size/flml/flashlight/cpu-latest?label=docker%20%28cpu%29&amp;logo=docker" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://vcpkg.info/port/flashlight-cuda" rel="nofollow"><img src="https://camo.githubusercontent.com/bfac46c2fd265af40fdbc53a1d6e8b40ac3c9c4030fc00a31f97352de6caf83f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f64796e616d69632f6a736f6e3f636f6c6f723d6f72616e6765266c6162656c3d676574253230253238637564612532392671756572793d6e616d652675726c3d68747470732533412532462532467261772e67697468756275736572636f6e74656e742e636f6d2532466d6963726f736f66742532467663706b672532466d6173746572253246706f727473253246666c6173686c696768742d637564612532467663706b672e6a736f6e267072656669783d7663706b67253230696e7374616c6c253230" alt="使用 vcpkg 安装 CUDA 后端" data-canonical-src="https://img.shields.io/badge/dynamic/json?color=orange&amp;label=get%20%28cuda%29&amp;query=name&amp;url=https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2Fvcpkg%2Fmaster%2Fports%2Fflashlight-cuda%2Fvcpkg.json&amp;prefix=vcpkg%20install%20" style="max-width: 100%;"></a>
<a href="https://vcpkg.info/port/flashlight-cpu" rel="nofollow"><img src="https://camo.githubusercontent.com/1ca8dc99dd7de85dbaff0c4a0c555e3caba12d0d5db442c0bef87dca9010d547/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f64796e616d69632f6a736f6e3f636f6c6f723d6f72616e6765266c6162656c3d6765742532302532386370752532392671756572793d6e616d652675726c3d68747470732533412532462532467261772e67697468756275736572636f6e74656e742e636f6d2532466d6963726f736f66742532467663706b672532466d6173746572253246706f727473253246666c6173686c696768742d6370752532467663706b672e6a736f6e267072656669783d7663706b67253230696e7374616c6c253230" alt="使用 vcpkg 安装 CPU 后端" data-canonical-src="https://img.shields.io/badge/dynamic/json?color=orange&amp;label=get%20%28cpu%29&amp;query=name&amp;url=https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2Fvcpkg%2Fmaster%2Fports%2Fflashlight-cpu%2Fvcpkg.json&amp;prefix=vcpkg%20install%20" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flashlight 是一个快速、灵活的机器学习库，由 Facebook AI Research 以及 Torch、TensorFlow、Eigen 和 Deep Speech 的创建者完全用 C++ 编写。其核心特点包括：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全面的内部可修改性，</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包括</font></font><a href="/flashlight/flashlight/blob/main/flashlight/fl/tensor/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于张量计算的内部 API</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占用空间小</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，核心时钟大小低于 10 MB，C++ 行数为 20k。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高性能默认设置通过</font></font></strong><font style="vertical-align: inherit;"></font><a href="https://github.com/arrayfire/arrayfire"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArrayFire</font></font></em></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张量库使用现代 C++ 进行即时内核编译</font><font style="vertical-align: inherit;">
。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强调效率和规模。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C++ 的本机支持和简单的可扩展性使 Flashlight 成为一个强大的研究框架，可以快速迭代新的实验设置和算法，几乎没有任何意见，并且不会牺牲性能。在单个存储库中，Flashlight 提供了</font><font style="vertical-align: inherit;">用于跨多个领域研究的</font></font><a href="https://github.com/flashlight/flashlight/tree/master/flashlight/app"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序：</font></font></a><font style="vertical-align: inherit;"></font></p>
<ul dir="auto">
<li><a href="https://github.com/flashlight/flashlight/tree/master/flashlight/app/asr"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动语音识别</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（以前称为</font></font><a href="https://github.com/flashlight/wav2letter/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">wav2letter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目）—</font></font><a href="/flashlight/flashlight/blob/main/flashlight/app/asr"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="/flashlight/flashlight/blob/main/flashlight/app/asr/tutorial"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教程</font></font></a></li>
<li><a href="/flashlight/flashlight/blob/main/flashlight/app/imgclass"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像分类</font></font></a></li>
<li><a href="/flashlight/flashlight/blob/main/flashlight/app/objdet"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">物体检测</font></font></a></li>
<li><a href="/flashlight/flashlight/blob/main/flashlight/app/lm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语言建模</font></font></a></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-project-layout" class="anchor" aria-hidden="true" tabindex="-1" href="#project-layout"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目布局</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒分为几个部分：</font></font></p>
<ul dir="auto">
<li><a href="/flashlight/flashlight/blob/main/flashlight/lib"><strong><code>flashlight/lib</code></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包含用于音频处理等的内核和独立实用程序。</font></font></li>
<li><a href="/flashlight/flashlight/blob/main/flashlight/fl"><strong><code>flashlight/fl</code></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是核心张量接口和神经网络库，</font><font style="vertical-align: inherit;">默认使用</font></font><a href="https://github.com/arrayfire/arrayfire"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArrayFire张量库。</font></font></a><font style="vertical-align: inherit;"></font></li>
<li><a href="/flashlight/flashlight/blob/main/flashlight/pkg"><strong><code>flashlight/pkg</code></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是构建在核心上的语音、视觉和文本的域包。</font></font></li>
<li><a href="/flashlight/flashlight/blob/main/flashlight/app"><strong><code>flashlight/app</code></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是核心库在跨领域机器学习中的应用。</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-quickstart" class="anchor" aria-hidden="true" tabindex="-1" href="#quickstart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，</font></font><a href="#building-and-installing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建并安装 Flashlight</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并将</font></font><a href="#building-your-own-project-with-flashlight"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其链接到您自己的项目</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><a href="https://fl.readthedocs.io/en/latest/modules.html#sequential" rel="nofollow"><code>Sequential</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">形成 Flashlight 的序列</font></font><a href="https://fl.readthedocs.io/en/latest/modules.html#module" rel="nofollow"><code>Module</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以进行链接计算。</font></font></p>
<details><summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现一个简单的卷积网络很容易。</font></font></summary>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">&lt;</span>flashlight/fl/flashlight.h<span class="pl-pds">&gt;</span></span>

Sequential model;

model.add(View(fl::Shape({IM_DIM, IM_DIM, <span class="pl-c1">1</span>, -<span class="pl-c1">1</span>})));
model.add(Conv2D(
    <span class="pl-c1">1</span> <span class="pl-c"><span class="pl-c">/*</span> input channels <span class="pl-c">*/</span></span>,
    <span class="pl-c1">32</span> <span class="pl-c"><span class="pl-c">/*</span> output channels <span class="pl-c">*/</span></span>,
    <span class="pl-c1">5</span> <span class="pl-c"><span class="pl-c">/*</span> kernel width <span class="pl-c">*/</span></span>,
    <span class="pl-c1">5</span> <span class="pl-c"><span class="pl-c">/*</span> kernel height <span class="pl-c">*/</span></span>,
    <span class="pl-c1">1</span> <span class="pl-c"><span class="pl-c">/*</span> stride x <span class="pl-c">*/</span></span>,
    <span class="pl-c1">1</span> <span class="pl-c"><span class="pl-c">/*</span> stride y <span class="pl-c">*/</span></span>,
    PaddingMode::SAME; <span class="pl-c"><span class="pl-c">/*</span> padding mode <span class="pl-c">*/</span></span>,
    PaddingMode::SAME; <span class="pl-c"><span class="pl-c">/*</span> padding mode <span class="pl-c">*/</span></span>));
model.add(ReLU());
model.add(Pool2D(
    <span class="pl-c1">2</span> <span class="pl-c"><span class="pl-c">/*</span> kernel width <span class="pl-c">*/</span></span>,
    <span class="pl-c1">2</span> <span class="pl-c"><span class="pl-c">/*</span> kernel height <span class="pl-c">*/</span></span>,
    <span class="pl-c1">2</span> <span class="pl-c"><span class="pl-c">/*</span> stride x <span class="pl-c">*/</span></span>,
    <span class="pl-c1">2</span> <span class="pl-c"><span class="pl-c">/*</span> stride y <span class="pl-c">*/</span></span>));
model.add(Conv2D(<span class="pl-c1">32</span>, <span class="pl-c1">64</span>, <span class="pl-c1">5</span>, <span class="pl-c1">5</span>, <span class="pl-c1">1</span>, <span class="pl-c1">1</span>, PaddingMode::SAME, PaddingMode::SAME));
model.add(ReLU());
model.add(Pool2D(<span class="pl-c1">2</span>, <span class="pl-c1">2</span>, <span class="pl-c1">2</span>, <span class="pl-c1">2</span>));
model.add(View(fl::Shape({<span class="pl-c1">7</span> * <span class="pl-c1">7</span> * <span class="pl-c1">64</span>, -<span class="pl-c1">1</span>})));
model.add(Linear(<span class="pl-c1">7</span> * <span class="pl-c1">7</span> * <span class="pl-c1">64</span>, <span class="pl-c1">1024</span>));
model.add(ReLU());
model.add(Dropout(<span class="pl-c1">0.5</span>));
model.add(Linear(<span class="pl-c1">1024</span>, <span class="pl-c1">10</span>));
model.add(LogSoftmax());</pre><div class="zeroclipboard-container">
   
  </div></div>
<p dir="auto">Performing forward and backward computation is straightforwards:</p>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">auto</span> output = model.forward(input);
<span class="pl-k">auto</span> loss = categoricalCrossEntropy(output, target);
loss.backward();</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="auto output = model.forward(input);
auto loss = categoricalCrossEntropy(output, target);
loss.backward();" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://fl.readthedocs.io/en/latest/mnist.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MNIST 示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取完整教程，包括训练循环和数据集抽象。</font></font></p>
<p dir="auto"><a href="https://fl.readthedocs.io/en/latest/variable.html" rel="nofollow"><code>Variable</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一种基于磁带的抽象，包装了</font></font><a href="https://github.com/flashlight/flashlight/blob/main/flashlight/fl/tensor/TensorBase.h"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flashlight 张量</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。 Flashlight 中</font><font style="vertical-align: inherit;">基于磁带的</font></font><a href="https://fl.readthedocs.io/en/latest/autograd.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动微分</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">很简单，并且可以按照您的预期工作。</font></font></p>
<details><summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动评分示例</font></font></summary>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">auto</span> A = Variable(fl::rand({<span class="pl-c1">1000</span>, <span class="pl-c1">1000</span>}), <span class="pl-c1">true</span> <span class="pl-c"><span class="pl-c">/*</span> calcGrad <span class="pl-c">*/</span></span>);
<span class="pl-k">auto</span> B = <span class="pl-c1">2.0</span> * A;
<span class="pl-k">auto</span> C = <span class="pl-c1">1.0</span> + B;
<span class="pl-k">auto</span> D = log(C);
D.backward(); <span class="pl-c"><span class="pl-c">//</span> populates A.grad() along with gradients for B, C, and D.</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="auto A = Variable(fl::rand({1000, 1000}), true /* calcGrad */);
auto B = 2.0 * A;
auto C = 1.0 + B;
auto D = log(C);
D.backward(); // populates A.grad() along with gradients for B, C, and D." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<h2 tabindex="-1" dir="auto"><a id="user-content-building-and-installing" class="anchor" aria-hidden="true" tabindex="-1" href="#building-and-installing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">搭建和安装</font></font></h2>
<p dir="auto"><a href="#library-installation-with-vcpkg"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font><code>vcpkg</code></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="#building-and-running-flashlight-with-docker"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Docker</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> |</font></font><a href="#building-from-source"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来源</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="#from-source-build-with-vcpkg"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从来源与</font></font><code>vcpkg</code></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|</font></font><a href="#building-your-own-project-with-flashlight"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用手电筒构建您的项目</font></font></strong></a></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-requirements" class="anchor" aria-hidden="true" tabindex="-1" href="#requirements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编译至少需要：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有良好 C++17 支持的 C++ 编译器（例如 gcc/g++ &gt;= 7）</font></font></li>
<li><a href="https://cmake.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CMake</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> — 版本 3.10 或更高版本，以及</font></font><code>make</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于 Linux 的操作系统。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><a href="#building-from-source"><font style="vertical-align: inherit;">如果从源代码构建</font></a><font style="vertical-align: inherit;">，请参阅</font></font><a href="#dependencies"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完整的依赖项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表以获取更多详细信息</font><font style="vertical-align: inherit;">。</font></font><a href="#building-from-source"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/flashlight/flashlight/blob/main/bindings/python/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以在此处找到</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关构建/安装 Python 绑定的说明</font><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-flashlight-build-setups" class="anchor" aria-hidden="true" tabindex="-1" href="#flashlight-build-setups"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒构建设置</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="#project-layout"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如上所述</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，手电筒可以分为几个组件</font><font style="vertical-align: inherit;">。每个组件都可以通过指定正确的</font></font><a href="#build-options"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建选项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来增量构建。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用手电筒有两种方法：</font></font></p>
<ol dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为一个已安装的库</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，您可以将其链接到您自己的项目。这最适合构建依赖于 Flashlight 的独立应用程序。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过源内开发</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可以更改并重建 Flashlight 项目源。如果自定义/破解核心框架或 Flashlight 提供的</font></font><a href="/flashlight/flashlight/blob/main/flashlight/app"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序二进制文件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，这是最好的。</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒可以通过以下两种方式之一构建：</font></font></p>
<ol dir="auto">
<li><a href="#installing-flashlight-with-vcpkg"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><code>vcpkg</code></strong></a><font style="vertical-align: inherit;"></font><a href="https://github.com/microsoft/vcpkg"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C++ 包管理</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">器</font><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="#building-from-source"><strong><font style="vertical-align: inherit;"></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据需要</font><a href="#building-from-source"><strong><font style="vertical-align: inherit;">从源安装依赖项。</font></strong></a></font></li>
</ol>
<h3 tabindex="-1" dir="auto"><a id="user-content-installing-flashlight-with-vcpkg" class="anchor" aria-hidden="true" tabindex="-1" href="#installing-flashlight-with-vcpkg"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装手电筒</font></font><code>vcpkg</code></h3>
<h4 tabindex="-1" dir="auto"><a id="user-content-library-installation-with-vcpkg" class="anchor" aria-hidden="true" tabindex="-1" href="#library-installation-with-vcpkg"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库安装</font></font><code>vcpkg</code></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒最容易构建和安装</font></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。 CUDA 和 CPU 后端均受</font></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.对于任一后端，首先安装</font></font><a href="https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Intel MKL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。对于 CUDA 后端，安装</font></font><a href="https://developer.nvidia.com/cuda-downloads" rel="nofollow"><code>CUDA</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&gt;= 9.2</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://docs.nvidia.com/deeplearning/cudnn/install-guide/index.html" rel="nofollow"><code>cuDNN</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://docs.nvidia.com/deeplearning/nccl/install-guide/index.html" rel="nofollow"><code>NCCL</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。然后，</font></font><a href="https://github.com/microsoft/vcpkg#getting-started"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font><code>vcpkg</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后，使用以下命令安装库和核心：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./vcpkg/vcpkg install flashlight-cuda <span class="pl-c"><span class="pl-c">#</span> CUDA backend, OR</span>
./vcpkg/vcpkg install flashlight-cpu  <span class="pl-c"><span class="pl-c">#</span> CPU backend</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./vcpkg/vcpkg install flashlight-cuda # CUDA backend, OR
./vcpkg/vcpkg install flashlight-cpu  # CPU backend" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要安装</font></font><a href="/flashlight/flashlight/blob/main/flashlight/app"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flashlight 应用程序</font></font></a><font style="vertical-align: inherit;"></font><code>./vcpkg search flashlight-cuda</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，请通过运行或</font><font style="vertical-align: inherit;">检查可安装的功能</font></font><code>./vcpkg search flashlight-cpu</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。每个应用程序都是一个“功能”：例如，</font></font><code>./vcpkg install flashlight-cuda[asr]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装带有 CUDA 后端的 ASR 应用程序。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是当前支持的功能列表（针对 和</font></font><a href="https://vcpkg.info/port/flashlight-cuda" rel="nofollow"><code>flashlight-cuda</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font><a href="https://vcpkg.info/port/flashlight-cpu" rel="nofollow"><code>flashlight-cpu</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>flashlight-{cuda/cpu}[lib]      # Flashlight libraries
flashlight-{cuda/cpu}[nn]       # Flashlight neural net library
flashlight-{cuda/cpu}[asr]      # Flashlight speech recognition app
flashlight-{cuda/cpu}[lm]       # Flashlight language modeling app
flashlight-{cuda/cpu}[imgclass] # Flashlight image classification app
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="flashlight-{cuda/cpu}[lib]      # Flashlight libraries
flashlight-{cuda/cpu}[nn]       # Flashlight neural net library
flashlight-{cuda/cpu}[asr]      # Flashlight speech recognition app
flashlight-{cuda/cpu}[lm]       # Flashlight language modeling app
flashlight-{cuda/cpu}[imgclass] # Flashlight image classification app" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flashlight</font></font><a href="/flashlight/flashlight/blob/main/flashlight/app"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序二进制文件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">也是针对所选功能构建的，并安装到</font></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装树的</font></font><code>tools</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录中。</font></font></p>
<p dir="auto"><a href="#with-a-vcpkg-flashlight-installation"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用CMake</font></font><a href="https://vcpkg.readthedocs.io/en/latest/examples/installing-and-using-packages/#cmake" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工具链集成</font></font></a><font style="vertical-align: inherit;"><a href="#with-a-vcpkg-flashlight-installation"><font style="vertical-align: inherit;">将 Flashlight 集成到您自己的项目中</font></a><font style="vertical-align: inherit;">非常简单</font><font style="vertical-align: inherit;">。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-from-source-build-with-vcpkg" class="anchor" aria-hidden="true" tabindex="-1" href="#from-source-build-with-vcpkg"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源代码构建</font></font><code>vcpkg</code></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，使用以下命令安装您选择的后端的依赖项</font></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（单击展开下面的内容）：</font></font></p>
<details><summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 vcpkg 安装 CUDA 后端依赖项</font></font></summary>
<p dir="auto">To build the Flashlight CUDA backend from source using dependencies installed with <code>vcpkg</code>, install <a href="https://developer.nvidia.com/cuda-downloads" rel="nofollow"><code>CUDA</code> &gt;= 9.2</a>, <a href="https://docs.nvidia.com/deeplearning/cudnn/install-guide/index.html" rel="nofollow"><code>cuDNN</code></a>, <a href="https://docs.nvidia.com/deeplearning/nccl/install-guide/index.html" rel="nofollow"><code>NCCL</code></a>, and <a href="https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html" rel="nofollow">Intel MKL</a>, then build the rest of the dependencies for the CUDA backend based on which Flashlight features you'd like to build:</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./vcpkg install \
    cuda intel-mkl fftw3 cub kenlm                <span class="pl-cce">\ </span><span class="pl-c"><span class="pl-c">#</span> if building flashlight libraries</span>
    arrayfire[cuda] cudnn nccl openmpi cereal stb <span class="pl-cce">\ </span><span class="pl-c"><span class="pl-c">#</span> if building the flashlight neural net library</span>
    gflags glog                                   <span class="pl-cce">\ </span><span class="pl-c"><span class="pl-c">#</span> if building any flashlight apps</span>
    libsndfile                                    <span class="pl-cce">\ </span><span class="pl-c"><span class="pl-c">#</span> if building the flashlight asr app</span>
    gtest                                           <span class="pl-c"><span class="pl-c">#</span> optional, if building tests</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./vcpkg install \
    cuda intel-mkl fftw3 cub kenlm                \ # if building flashlight libraries
    arrayfire[cuda] cudnn nccl openmpi cereal stb \ # if building the flashlight neural net library
    gflags glog                                   \ # if building any flashlight apps
    libsndfile                                    \ # if building the flashlight asr app
    gtest                                           # optional, if building tests" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<details><summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 vcpkg 安装 CPU 后端依赖项</font></font></summary>
<p dir="auto">To build the Flashlight CPU backend from source using dependencies installed with <code>vcpkg</code>, install <a href="https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html" rel="nofollow">Intel MKL</a>, then build the rest of the dependencies for the CPU backend based on which Flashlight features you'd like to build:</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./vcpkg install \
    intel-mkl fftw3 kenlm                              <span class="pl-cce">\ </span><span class="pl-c"><span class="pl-c">#</span> for flashlight libraries</span>
    arrayfire[cpu] gloo[mpi] openmpi onednn cereal stb <span class="pl-cce">\ </span><span class="pl-c"><span class="pl-c">#</span> for the flashlight neural net library</span>
    gflags glog                                        <span class="pl-cce">\ </span><span class="pl-c"><span class="pl-c">#</span> for the flashlight runtime pkg (any flashlight apps using it)</span>
    libsndfile                                         <span class="pl-cce">\ </span><span class="pl-c"><span class="pl-c">#</span> for the flashlight speech pkg</span>
    gtest                                                <span class="pl-c"><span class="pl-c">#</span> optional, for tests</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./vcpkg install \
    intel-mkl fftw3 kenlm                              \ # for flashlight libraries
    arrayfire[cpu] gloo[mpi] openmpi onednn cereal stb \ # for the flashlight neural net library
    gflags glog                                        \ # for the flashlight runtime pkg (any flashlight apps using it)
    libsndfile                                         \ # for the flashlight speech pkg
    gtest                                                # optional, for tests" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<h5 tabindex="-1" dir="auto"><a id="user-content-build-using-the-vcpkg-toolchain-file" class="anchor" aria-hidden="true" tabindex="-1" href="#build-using-the-vcpkg-toolchain-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工具链文件构建</font></font></h5>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用这些依赖项从源代码构建 Flashlight，请克隆存储库：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/flashlight/flashlight.git <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">cd</span> flashlight
mkdir -p build <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">cd</span> build</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/flashlight/flashlight.git &amp;&amp; cd flashlight
mkdir -p build &amp;&amp; cd build" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，使用CMake</font></font><a href="https://github.com/microsoft/vcpkg/blob/master/docs/users/integration.md#cmake-toolchain-file-recommended-for-open-source-cmake-projects"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工具链</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源代码构建</font><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>cmake .. \
    -DCMAKE_BUILD_TYPE=Release \
    -DFL_BUILD_ARRAYFIRE=ON \
    -DCMAKE_TOOLCHAIN_FILE=[path to your vcpkg clone]/scripts/buildsystems/vcpkg.cmake
make -j<span class="pl-s"><span class="pl-pds">$(</span>nproc<span class="pl-pds">)</span></span>
make install -j<span class="pl-s"><span class="pl-pds">$(</span>nproc<span class="pl-pds">)</span></span> <span class="pl-c"><span class="pl-c">#</span> only if you want to install Flashlight for external use</span></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要构建 Flashlight 功能的子集，请参阅下面的</font></font><a href="#build-options"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建选项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-building-from-source" class="anchor" aria-hidden="true" tabindex="-1" href="#building-from-source"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源头构建</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要从源代码构建，请首先安装以下</font></font><a href="#dependencies"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">依赖项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。大多数都可以通过系统的本地包管理器使用。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果在本地系统上找不到，下面标记的一些依赖项将自动下载并安装。</font></font><code>FL_BUILD_STANDALONE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确定此行为 - 如果禁用，则在构建 Flashlight 时将不会下载和构建依赖项。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装所有依赖项后</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，克隆存储库：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/flashlight/flashlight.git <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">cd</span> flashlight
mkdir -p build <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">cd</span> build</pre><div class="zeroclipboard-container">
     
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后使用以下命令构建所有手电筒组件：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>cmake .. -DCMAKE_BUILD_TYPE=Release -DFL_BUILD_ARRAYFIRE=ON [...build options]
make -j$(nproc)
make install
</code></pre><div class="zeroclipboard-container">
   
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置</font></font><code>MKLROOT</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量（</font></font><code>export MKLROOT=/opt/intel/oneapi/mkl/latest</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>export MKLROOT=/opt/intel/mkl</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在大多数基于 Linux 的系统上）可以帮助 CMake 找到 Intel MKL（如果最初未找到）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要构建 Flashlight 功能/应用程序的较小子集，请参阅下面的</font></font><a href="#build-options"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建选项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取完整的选项列表。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要将 Flashlight 安装在自定义目录中，请使用 CMake 的</font></font><a href="https://cmake.org/cmake/help/v3.10/variable/CMAKE_INSTALL_PREFIX.html" rel="nofollow"><code>CMAKE_INSTALL_PREFIX</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数。可以使用 CMake 的参数将 Flashlight 库构建为共享库</font></font><a href="https://cmake.org/cmake/help/v3.10/variable/BUILD_SHARED_LIBS.html" rel="nofollow"><code>BUILD_SHARED_LIBS</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flashlight 使用现代 CMake 和</font></font><code>IMPORTED</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大多数依赖项的目标。如果未找到依赖项，则传递</font></font><code>-D&lt;package&gt;_DIR</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到</font></font><code>cmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令或导出</font></font><code>&lt;package&gt;_DIR</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为等于路径的环境变量</font></font><code>&lt;package&gt;Config.cmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以帮助查找系统上的依赖项。请参阅</font></font><a href="https://cmake.org/cmake/help/v3.10/command/find_package.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多详细信息。如果 CMake 无法找到包，请在创建您自己的包之前检查是否</font><font style="vertical-align: inherit;">已经创建了相应的</font></font><a href="https://github.com/flashlight/flashlight/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-minimal-setup-on-macos" class="anchor" aria-hidden="true" tabindex="-1" href="#minimal-setup-on-macos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS 上的最小设置</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 MacOS 上，ArrayFire 可以通过自制程序安装，并且 Flashlight 核心可以按如下方式构建：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>brew install arrayfire
cmake .. \
      -DFL_ARRAYFIRE_USE_OPENCL=ON \
      -DFL_USE_ONEDNN=OFF \
      -DFL_BUILD_TESTS=OFF \
      -DFL_BUILD_EXAMPLES=OFF \
      -DFL_BUILD_SCRIPTS=OFF \
      -DFL_BUILD_DISTRIBUTED=OFF
make -j$(nproc)
</code></pre><div class="zeroclipboard-container">
    
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-dependencies" class="anchor" aria-hidden="true" tabindex="-1" href="#dependencies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">依赖关系</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>*</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果系统上找不到</font><font style="vertical-align: inherit;">标记为 的依赖项，则会自动从源下载并构建依赖项。</font><font style="vertical-align: inherit;">设置</font></font><code>FL_BUILD_STANDALONE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>OFF</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁用此行为。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>^</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果启用了分布式训练进行构建，则需要</font><font style="vertical-align: inherit;">标记为 的依赖项（ </font></font><code>FL_BUILD_DISTRIBUTED</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 请参阅下面的</font></font><a href="#build-options"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建选项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。所有应用程序都需要分布式培训。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标记为 的依赖项</font></font><code>†</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可通过 进行安装</font></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。请参阅上面</font></font><a href="#from-source-build-with-vcpkg"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装这些依赖项的说明，</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以进行 Flashlight 从源代码构建。</font></font></p>
<table>
<thead>
  <tr>
    <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成分</font></font></th>
    <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后端</font></font></th>
    <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">依赖关系</font></font></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图书馆</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不同的</font></font></td>
    <td><a href="https://developer.nvidia.com/cuda-downloads" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CUDA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &gt;= 9.2，</font></font><a href="https://github.com/nvidia/cub"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CUB</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> *†（如果 CUDA &lt; 11）</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中央处理器</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BLAS 库（</font></font><a href="https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Intel MKL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &gt;= 2018、OpenBLAS† 等）</font></font></td>
  </tr>
  <tr>
    <td rowspan="3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">核</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何</font></font></td>
    <td><a href="https://github.com/arrayfire/arrayfire#installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArrayFire</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &gt;= 3.7.3†、MPI 库^( </font></font><a href="https://www.open-mpi.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenMPI</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> † 等)、&nbsp;&nbsp;</font></font><a href="https://github.com/USCiLab/cereal"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">谷物</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*† &gt;= 1.3.0、</font></font><a href="https://github.com/nothings/stb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">stb</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> *†</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不同的</font></font></td>
    <td><a href="https://developer.nvidia.com/cuda-downloads" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CUDA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &gt;= 9.2、</font></font><a href="https://developer.nvidia.com/nccl" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NCCL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ^、</font></font><a href="https://developer.nvidia.com/cuDNN" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cuDNN</font></font></a></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中央处理器</font></font></td>
    <td><a href="https://github.com/oneapi-src/oneDNN"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">oneDNN</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> † &gt;= 2.5.2，</font></font><a href="https://github.com/facebookincubator/gloo"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gloo</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font><a href="https://github.com/facebookincubator/gloo/blob/01e2c2660cd43963ce1fe3e21220ac01f07d9a4b/docs/rendezvous.md#using-mpi"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带有 MPI</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）*^†</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序：全部</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何</font></font></td>
    <td><a href="https://github.com/google/glog"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google Glog</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> †、</font></font><a href="https://github.com/gflags/gflags"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gflags</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> †</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序：asr</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何</font></font></td>
    <td><a href="https://github.com/libsndfile/libsndfile"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">libsndfile</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> *† &gt;= 10.0.28，BLAS 库（</font></font><a href="https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit/download.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Intel MKL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &gt;= 2018、OpenBLAS† 等）、</font></font><a href="https://github.com/flashlight/text"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒/文本</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序：imgclass</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序：imgclass</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用： LM</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何</font></font></td>
    <td><a href="https://github.com/flashlight/text"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒/文字</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何</font></font></td>
    <td><a href="https://github.com/google/googletest"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google 测试（gtest，带 gmock）</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> *† &gt;= 1.10.0</font></font></td>
  </tr>
</tbody>
</table>
<h4 tabindex="-1" dir="auto"><a id="user-content-build-options" class="anchor" aria-hidden="true" tabindex="-1" href="#build-options"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建选项</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flashlight CMake 构建接受以下构建选项（</font></font><code>-D</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从命令行运行 CMake 时前缀为 ）：</font></font></p>
<table>
<thead>
  <tr>
    <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">姓名</font></font></th>
    <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项</font></font></th>
    <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认值</font></font></th>
    <th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_ARRAYFIRE</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 ArrayFire 后端构建 Flashlight。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果找不到，则下载/构建一些依赖项。</font></font></td>
  </tr>
  <tr>
    <td rowspan="3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_LIBRARIES</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建手电筒库。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建 Flashlight 神经网络库。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过分布式训练进行构建；应用程序所需的。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_CONTRIB</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建可进行重大更改的 contrib API。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_APPS</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建应用程序（见下文）。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_APP_ASR</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建自动语音识别应用程序。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_APP_IMGCLASS</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建图像分类应用程序。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_APP_LM</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建语言建模应用程序。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_APP_ASR_TOOLS</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建自动语音识别应用程序工具。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_测试</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建测试。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_EXAMPLES</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建示例。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FL_BUILD_实验</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离开</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建实验组件。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CMAKE_BUILD_TYPE</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://cmake.org/cmake/help/v3.10/variable/CMAKE_BUILD_TYPE.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">调试</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://cmake.org/cmake/help/v3.10/variable/CMAKE_BUILD_TYPE.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CMake 文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
  </tr>
  <tr>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CMAKE_INSTALL_PREFIX</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[目录]</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://cmake.org/cmake/help/v3.10/variable/CMAKE_INSTALL_PREFIX.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://cmake.org/cmake/help/v3.10/variable/CMAKE_INSTALL_PREFIX.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CMake 文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
  </tr>
</tbody>
</table>
<h3 tabindex="-1" dir="auto"><a id="user-content-building-your-own-project-with-flashlight" class="anchor" aria-hidden="true" tabindex="-1" href="#building-your-own-project-with-flashlight"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用手电筒构建您自己的项目</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flashlight 最容易与 CMake 关联。 Flashlight 在安装后导出以下 CMake 目标：</font></font></p>
<ul dir="auto">
<li><code>flashlight::flashlight</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">— 包含手电筒库以及手电筒核心 autograd 和神经网络库。</font></font></li>
<li><code>flashlight::fl_pkg_runtime</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">— 包含手电筒核心以及用于培训的常用实用程序（日志记录/标志/分布式实用程序）。</font></font></li>
<li><code>flashlight::fl_pkg_vision</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">— 包含手电筒核心以及视觉管道的常用实用程序。</font></font></li>
<li><code>flashlight::fl_pkg_text</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">— 包含手电筒核心以及处理文本数据的常用实用程序。</font></font></li>
<li><code>flashlight::fl_pkg_speech</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">— 包含手电筒核心以及处理语音数据的常用实用程序。</font></font></li>
<li><code>flashlight::fl_pkg_halide</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">— 包含手电筒核心和扩展件，可轻松与卤化物连接。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>project.cpp</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">给定一个包含并链接到 Flashlight 的</font><font style="vertical-align: inherit;">简单文件：</font></font></p>
<div class="highlight highlight-source-c++ notranslate position-relative overflow-auto" dir="auto"><pre>#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">&lt;</span>iostream<span class="pl-pds">&gt;</span></span>

#<span class="pl-k">include</span> <span class="pl-s"><span class="pl-pds">&lt;</span>flashlight/fl/flashlight.h<span class="pl-pds">&gt;</span></span>

<span class="pl-k">int</span> <span class="pl-en">main</span>() {
  <span class="pl-c1">fl::init</span>();
  fl::Variable <span class="pl-smi">v</span>(<span class="pl-c1">fl::full</span>({<span class="pl-c1">1</span>}, <span class="pl-c1">1</span>.), <span class="pl-c1">true</span>);
  <span class="pl-k">auto</span> result = v + <span class="pl-c1">10</span>;
  std::cout &lt;&lt; <span class="pl-s"><span class="pl-pds">"</span>Tensor value is <span class="pl-pds">"</span></span> &lt;&lt; result.<span class="pl-c1">tensor</span>() &lt;&lt; std::endl; <span class="pl-c"><span class="pl-c">//</span> 11.000</span>
  <span class="pl-k">return</span> <span class="pl-c1">0</span>;
}</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下 CMake 配置链接 Flashlight 和集包含目录：</font></font></p>
<div class="highlight highlight-source-cmake notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cmake_minimum_required</span>(<span class="pl-k">VERSION</span> 3.10)
<span class="pl-c1">set</span>(CMAKE_CXX_STANDARD 17)
<span class="pl-c1">set</span>(CMAKE_CXX_STANDARD_REQUIRED <span class="pl-k">ON</span>)

<span class="pl-c1">add_executable</span>(myProject project.cpp)

<span class="pl-c1">find_package</span>(flashlight <span class="pl-k">CONFIG</span> <span class="pl-k">REQUIRED</span>)
<span class="pl-c1">target_link_libraries</span>(myProject <span class="pl-k">PRIVATE</span> flashlight::flashlight)</pre><div class="zeroclipboard-container">
   
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-with-a-vcpkg-flashlight-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#with-a-vcpkg-flashlight-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带</font></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒安装</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您安装了 Flashlight ，则</font><font style="vertical-align: inherit;">可以通过运行以下命令来构建</font></font><code>vcpkg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上述 CMake 配置：</font></font><code>myProject</code><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cd</span> project <span class="pl-k">&amp;&amp;</span> mkdir build <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">cd</span> build
cmake .. \
  -DCMAKE_TOOLCHAIN_FILE=[path to vcpkg clone]/scripts/buildsystems/vcpkg.cmake \
  -DCMAKE_BUILD_TYPE=Release
make -j<span class="pl-s"><span class="pl-pds">$(</span>nproc<span class="pl-pds">)</span></span></pre><div class="zeroclipboard-container">
  
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-with-a-from-source-flashlight-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#with-a-from-source-flashlight-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用源头手电筒安装</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果使用 Flashlight 的源安装，CMake 将自动找到 Flashlight：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cd</span> project <span class="pl-k">&amp;&amp;</span> mkdir build <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">cd</span> build
cmake .. -DCMAKE_BUILD_TYPE=Release
make -j<span class="pl-s"><span class="pl-pds">$(</span>nproc<span class="pl-pds">)</span></span></pre><div class="zeroclipboard-container">
   
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果使用 来将 Flashlight 安装在自定义位置</font></font><code>CMAKE_INSTALL_PREFIX</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则</font></font><code>-Dflashlight_DIR=[install prefix]/share/flashlight/cmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为参数传递给</font></font><code>cmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令可以帮助 CMake 找到 Flashlight。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-building-and-running-flashlight-with-docker" class="anchor" aria-hidden="true" tabindex="-1" href="#building-and-running-flashlight-with-docker"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Docker 构建并运行 Flashlight</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flashlight 及其依赖项也可以使用提供的 Dockerfile 进行构建；</font><font style="vertical-align: inherit;">有关更多信息，</font><font style="vertical-align: inherit;">请参阅随附的</font></font><a href="/flashlight/flashlight/blob/main/.docker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 文档。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-contributing-and-contact" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing-and-contact"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献和联系</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联系方式：</font></font><a href="mailto:vineelkpratap@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vineelkpratap@fb.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="mailto:awni@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">awni@fb.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="mailto:jacobkahn@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">jacobkahn@fb.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="mailto:qiantong@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">qiantong@fb.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="mailto:antares@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">antares@fb.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="mailto:padentomasello@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">padentomasello</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> @fb.com 、
 </font></font><a href="mailto:jcai@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">jcai@fb.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、   </font></font><a href="mailto:gab@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gab@fb.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="mailto:vitaliy888@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vitaliy888@fb.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> , </font></font><a href="mailto:locronan@fb.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">locronan@fb.com</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒的开发非常活跃。</font><font style="vertical-align: inherit;">有关如何提供帮助的更多信息，</font><font style="vertical-align: inherit;">请参阅
</font></font><a href="/flashlight/flashlight/blob/main/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-acknowledgments" class="anchor" aria-hidden="true" tabindex="-1" href="#acknowledgments"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flashlight 的一些代码源自
</font></font><a href="https://github.com/arrayfire/arrayfire-ml/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">arrayfire-ml</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-citing" class="anchor" aria-hidden="true" tabindex="-1" href="#citing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用以下方式引用</font></font><a href="https://arxiv.org/abs/2201.12465" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@misc{kahn2022flashlight,
      title={Flashlight: Enabling Innovation in Tools for Machine Learning},
      author={Jacob Kahn and Vineel Pratap and Tatiana Likhomanenko and Qiantong Xu and Awni Hannun and Jeff Cai and Paden Tomasello and Ann Lee and Edouard Grave and Gilad Avidov and Benoit Steiner and Vitaliy Liptchinsky and Gabriel Synnaeve and Ronan Collobert},
      year={2022},
      eprint={2201.12465},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
</code></pre><div class="zeroclipboard-container">
    
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-license" class="anchor" aria-hidden="true" tabindex="-1" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手电筒已获得麻省理工学院许可。请参阅</font></font><a href="/flashlight/flashlight/blob/main/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多信息。</font></font></p>
</article></div>
