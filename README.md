# 咸蛋面板备份
<div class="container">
<h1>闲蛋中转面板是在原作者的面板基础上noobcfy大佬二次开发的一款多协议中转面板，首次开放公测发布于全球主机交流论坛。</h1>
<h3><p>官方介绍：</p></h3>
<p>本系统基于闲蛋中转面板 1.0.7 源码，二次开发，并取得原作者授权(本人在原版也曾是开源贡献者)。<br>
<strong>系统介绍：</strong></p>
<ul>
<li>支持多种转发方式</li>
<li>流量收集重做 区分上下行</li>
<li>新增插件管理模式</li>
<li>新增一键救援模式</li>
<li>多服务器、多用户、多端口管理</li>
<li>自动化达量停机、超时停机</li>
<li>轻量平台式管理，中转机无被控，无机型要求 nat、vps、vds、杜甫均可使用</li>
<li>一键脚本安装、更新 ，无门槛 上手快</li>
</ul>
<p>目前我自己也搭建过使用了一段时间，确实比以往的脚本方式方便了很多，很多功能都可以一键完成。</p>
<p>下面给介绍下安装和使用方法（截止到本文发布时间的闲蛋版本为v 1.4.0）。</p>
<h2>安装教程</h2>
<p>推荐使用官方一键安装脚本</p>
<pre><code>bash &lt;(wget --no-check-certificate -qO- 'https://sh.xdmb.xyz/xiandan/xd.sh')</code></pre>
<p>官方一键升级脚本</p>
<pre><code>bash &lt;(wget --no-check-certificate -qO- 'https://sh.xdmb.xyz/xiandan/xd.sh') update</code></pre>
<p>准备一台vps，推荐配置1c1g即可。通过一键脚本安装。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/1502881263.png" alt="请输入图片描述" loading="lazy"></p>
<p>中途会要求输入面板映射端口。我自己就添加了54321。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/719116900.png" alt="请输入图片描述" loading="lazy"></p>
<p>安装速度取决于你的机器性能和带宽，接下来就是耐心等待了。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/637667917.png" alt="请输入图片描述" loading="lazy"></p>
<p>安装完毕后耐心等待几分钟才能访问。访问地址就是 IP:端口号，默认的账号和密码都是admin</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/1932948517.png" alt="请输入图片描述" loading="lazy"></p>
<h2>面板界面介绍</h2>
<p><img src="https://heaid.top/usr/uploads/2021/06/1651677798.png" alt="请输入图片描述" loading="lazy"></p>
<p></p><div class="tab-container post_tab box-shadow-wrap-lg">
<ul class="nav no-padder b-b scroll-hide" role="tablist">
<li class="nav-item active" role="presentation"><a class="nav-link active" style="" data-toggle="tab" aria-controls="tabs-2c44049eff1b475396d347e501c221c7360" role="tab" data-target="#tabs-2c44049eff1b475396d347e501c221c7360">服务器监控</a></li><li class="nav-item " role="presentation"><a class="nav-link " style="" data-toggle="tab" aria-controls="tabs-5dca9fe531e55e3e8863df9ec3a27488141" role="tab" data-target="#tabs-5dca9fe531e55e3e8863df9ec3a27488141">统计分析</a></li><li class="nav-item " role="presentation"><a class="nav-link " style="" data-toggle="tab" aria-controls="tabs-ae559c0c302ac78f112354d1c536a916722" role="tab" data-target="#tabs-ae559c0c302ac78f112354d1c536a916722">服务器管理</a></li><li class="nav-item " role="presentation"><a class="nav-link " style="" data-toggle="tab" aria-controls="tabs-84b01916c54a9d85a95c257d7d193ae8363" role="tab" data-target="#tabs-84b01916c54a9d85a95c257d7d193ae8363">账号管理</a></li><li class="nav-item " role="presentation"><a class="nav-link " style="" data-toggle="tab" aria-controls="tabs-6b67439b82cca394d0a927098c727323404" role="tab" data-target="#tabs-6b67439b82cca394d0a927098c727323404">中转管理</a></li><li class="nav-item " role="presentation"><a class="nav-link " style="" data-toggle="tab" aria-controls="tabs-fb4581084003ec6a724ec80777e9abbb15" role="tab" data-target="#tabs-fb4581084003ec6a724ec80777e9abbb15">系统设置</a></li><li class="nav-item " role="presentation"><a class="nav-link " style="" data-toggle="tab" aria-controls="tabs-80232e9174768b04620204102210139f966" role="tab" data-target="#tabs-80232e9174768b04620204102210139f966">通知设置</a></li><li class="nav-item " role="presentation"><a class="nav-link " style="" data-toggle="tab" aria-controls="tabs-ec75f3991f43ac65aa53aa1c9466c0d9277" role="tab" data-target="#tabs-ec75f3991f43ac65aa53aa1c9466c0d9277">授权商城</a></li>
</ul>
<div class="tab-content no-border">
<div role="tabpanel" id="tabs-2c44049eff1b475396d347e501c221c7360" class="tab-pane fade active in">
<p></p>
<p>监控页面类似探针，可以看到服务器的各项状态。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/431653232.png" alt="请输入图片描述" loading="lazy"></p>
<p></p></div><div role="tabpanel" id="tabs-5dca9fe531e55e3e8863df9ec3a27488141" class="tab-pane fade  ">
<p></p>
<p>统计分析可以显示实时的图表</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/3631309881.png" alt="请输入图片描述" loading="lazy"></p>
<p></p></div><div role="tabpanel" id="tabs-ae559c0c302ac78f112354d1c536a916722" class="tab-pane fade  ">
<p></p>
<p>添加中转服务器的位置，管理服务器端口</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/4013962923.png" alt="请输入图片描述" loading="lazy"></p>
<p></p></div><div role="tabpanel" id="tabs-84b01916c54a9d85a95c257d7d193ae8363" class="tab-pane fade  ">
<p></p>
<p>管理账号的位置，闲蛋面板可以开放子账号授权使用中转服务器，分配服务器端口</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/3693515153.png" alt="请输入图片描述" loading="lazy"></p>
<p></p></div><div role="tabpanel" id="tabs-6b67439b82cca394d0a927098c727323404" class="tab-pane fade  ">
<p></p>
<p>管理转发，</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/2319830063.png" alt="请输入图片描述" loading="lazy"></p>
<p></p></div><div role="tabpanel" id="tabs-fb4581084003ec6a724ec80777e9abbb15" class="tab-pane fade  ">
<p></p>
<p>管理授权</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/534411878.png" alt="请输入图片描述" loading="lazy"></p>
<p></p></div><div role="tabpanel" id="tabs-80232e9174768b04620204102210139f966" class="tab-pane fade  ">
<p></p>
<p>设置发件可以通过邮件通知自己服务器是否掉线</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/3361833947.png" alt="请输入图片描述" loading="lazy"></p>
<p></p></div><div role="tabpanel" id="tabs-ec75f3991f43ac65aa53aa1c9466c0d9277" class="tab-pane fade  ">
<p></p>
<p>闲蛋面板分为免费版和付费版，付费版支持更多功能。普通人免费版也是够用的。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/95855856.png" alt="请输入图片描述" loading="lazy"></p>
<p></p></div>
</div>
</div><p></p>
<h2>上手教程</h2>
<h3>1. 添加服务器</h3>
<p>下面添加一台服务器并添加转发。</p>
<p>点击服务器管理，添加服务器</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/518124646.png" alt="请输入图片描述" loading="lazy"></p>
<p>添加完毕后会以卡片的形式显示出来</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/1956503259.png" alt="image.png" loading="lazy"></p>
<h3>3. 安装插件</h3>
<p>点击配置会显示插件，免费版只能使用iptalbe，付费版可以使用下面更多的插件工具。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/1287976158.png" alt="image.png" loading="lazy"></p>
<p>下图展示了，所有插件全部安装完毕后的功能（注意安装好插件必须开启，后面才能使用，安装好插件，如果关闭状态下也是无法使用的）</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/1618492226.png" alt="image.png" loading="lazy"></p>
<p>根据你的需求来决定使用哪些插件。</p>
<h3>4. 添加服务器端口</h3>
<p>回到卡片页面，点击服务器上的端口维护，点击添加，最后点击确定。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/3597378542.png" alt="image.png" loading="lazy"></p>
<h3>5. 端口分配</h3>
<p>点击账号管理，默认的只有admin账户，如果你只是自用可以把服务器端口分配给admin账户即可，如果你想给别人分配，点击开通账号，新建一个用户即可。</p>
<p>点击你想分配的账号卡片上的端口分配，然后点击弹出菜单中的分配端口</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/679996723.png" alt="image.png" loading="lazy"></p>
<p>在右侧菜单中选择你刚刚添加的服务器，在选择你要分配的端口，如果全部添加选择分配所有即可</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/2946608326.png" alt="image.png" loading="lazy"></p>
<h3>6. 添加转发</h3>
<p>点击中转管理，顶部左侧admin处可以选择账号，右侧可以选择服务器。选择好刚刚添加好的服务器后，下方会展示出10个刚刚我们添加的10个端口信息。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/2167324407.png" alt="image.png" loading="lazy"></p>
<p>选择一个端口卡片，点击启用，选择好中转插件（注意服务器安装好的插件必须在服务器管理中开启，此处才会显示），这里我们中转一个被墙了的ip的22端口做测试。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/668229183.png" alt="image.png" loading="lazy"></p>
<p>点击确定后，点击故障检测查看，没有显示故障就代表中转成功。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/4098739309.png" alt="image.png" loading="lazy"></p>
<p>在finalshell里添加好中转后的地址和端口。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/83380910.png" alt="image.png" loading="lazy"></p>
<p>成功连接</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/348544133.png" alt="image.png" loading="lazy"></p>
<p>以上是简单的上手教程。</p>
<h3>7. 隧道转发</h3>
<p></p><div class="tip inlineBlock warning">
闲蛋面板提供了gost和echo隧道转发，需要注意的是这两种隧道转发是授权后才可以使用的。
</div><p></p>
<p>在服务器管理页面安装好插件后，启用。</p>
<p>下面以echo+wss隧道中转做演示，闲蛋的gost和echo隧道转发步骤都一样</p>
<p>比如我们搭建了一个ssr要中转的地址为a12.wuxiujiaqi.xyz端口为54439</p>
<p>在中转管理选择好echo+wss隧道中转，地址添加a12.wuxiujiaqi.xyz端口添加一个除了54439以外的其他端口（此端口为隧道端口），这里我随意添加了一个54420</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/3467600529.png" alt="image.png" loading="lazy"></p>
<p>确定后，会显示命令</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/637430932.png" alt="image.png" loading="lazy"></p>
<p>把此命令复制到落地机上执行,询问代理节点地址时直接默认即可，此处的询问代理端口请输入54439</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/3648526969.png" alt="image.png" loading="lazy"></p>
<p>最后选择开机自动启动，显示active（running）表示正常运行。</p>
<p><img src="https://heaid.top/usr/uploads/2021/06/982256661.png" alt="image.png" loading="lazy"></p>
<p>最后测试节点是否连通。</p>
<h3>8. 隧道转发（中间加一层跳板）</h3>
<blockquote>
<p>加一层跳板的意思顾名思义就是两层转发</p>
<p>比如你有一台垃圾美国小鸡，国内连接非常慢。你就可以通过在香港中间加一层转发来给美国小鸡加速</p>
<p>当然普通转发两层也可以实现，但是隧道更加安全，使用闲蛋隧道转发也很方便。</p>
<p>举例：</p>
<p>国内机：guoneiji.com 端口1</p>
<p>跳板机：tiaobanji.com端口2</p>
<p>落地机：luodiji.com 端口3</p>
</blockquote>
<p>中转的方式为， 国内机→gost隧道→香港（跳板机）→美国（落地机）</p>
<p>在落地机上搭建代理，luodiji.com 端口 3</p>
<p>打开闲蛋面板，在中转管理找到国内机的端口1，添加跳板机的地址和端口，点击确定</p>
<p><img src="https://heaid.top/usr/uploads/2021/07/2224561324.png" alt="image.png" loading="lazy"></p>
<p>然后，中转管理找到跳板机的端口2，添加好落地机的地址和端口，这里注意要勾选gost服务端</p>
<p><img src="https://heaid.top/usr/uploads/2021/07/1242403313.png" alt="image.png" loading="lazy"></p>
<p>这样你的代理地址就成为了xiandan.gq端口1</p>
</div>
