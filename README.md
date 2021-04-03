
### Splunk
Consultas e monitoramento com splunk, configurações e exemplos de query para uso de volumetria de dados.

#### 1. Iniciando o Splunk na linha de comando com MAC.

<pre style="white-space:pre;" class="line-numbers pre_js"><code class="pre_js"># <span class="token maybe-class-name">Mac</span> – iniciando o <span class="token maybe-class-name">Splunk</span> pela primeira vez
localhost<span class="token operator">:</span><span class="token operator">~</span>wbianchi$ splunk start <span class="token operator">--</span>accept<span class="token operator">-</span>license

<span class="token maybe-class-name">Splunk</span><span class="token operator">&gt;</span> <span class="token maybe-class-name">See</span> your world<span class="token punctuation">.</span> <span class="token property-access"><span class="token maybe-class-name">Maybe</span></span> wish you hadn't<span class="token punctuation">.</span>

<span class="token property-access"><span class="token maybe-class-name">Checking</span></span> prerequisites<span class="token spread operator">...</span>
<span class="token maybe-class-name">Checking</span> http port <span class="token punctuation">[</span><span class="token number">8000</span><span class="token punctuation">]</span><span class="token operator">:</span> open
<span class="token maybe-class-name">Checking</span> mgmt port <span class="token punctuation">[</span><span class="token number">8089</span><span class="token punctuation">]</span><span class="token operator">:</span> open
<span class="token maybe-class-name">Checking</span> configuration<span class="token spread operator">...</span>
<span class="token maybe-class-name">Done</span><span class="token punctuation">.</span>

<span class="token property-access"><span class="token maybe-class-name">Checking</span></span> index directory<span class="token spread operator">...</span>

<span class="token maybe-class-name">Validated</span> databases<span class="token operator">:</span>
 _audit _blocksignature _internal _thefishbucket history main summary

<span class="token maybe-class-name">Done</span><span class="token punctuation">.</span>

<span class="token property-access"><span class="token maybe-class-name">Success</span></span><span class="token punctuation">.</span>

<span class="token property-access"><span class="token maybe-class-name">Checking</span></span> conf files <span class="token keyword">for</span> typos<span class="token spread operator">...</span>

<span class="token maybe-class-name">All</span> preliminary checks passed<span class="token punctuation">.</span>
<span class="token property-access"><span class="token maybe-class-name">Starting</span></span> splunk server <span class="token function">daemon</span> <span class="token punctuation">(</span>splunkd<span class="token punctuation">)</span><span class="token spread operator">...</span>
<span class="token maybe-class-name">Done</span><span class="token punctuation">.</span>
<span class="token property-access"><span class="token maybe-class-name">Starting</span></span> splunkweb<span class="token spread operator">...</span>
<span class="token maybe-class-name">Done</span><span class="token punctuation">.</span>

<span class="token property-access"><span class="token maybe-class-name">If</span></span> you <span class="token keyword">get</span> stuck<span class="token punctuation">,</span> we're here to help<span class="token punctuation">.</span>
<span class="token property-access"><span class="token maybe-class-name">Look</span></span> <span class="token keyword">for</span> answers here<span class="token operator">:</span> http<span class="token operator">:</span><span class="token operator">/</span><span class="token operator">/</span>docs<span class="token punctuation">.</span><span class="token property-access">splunk</span><span class="token punctuation">.</span><span class="token property-access">com</span><span class="token operator">/</span><span class="token maybe-class-name">Documentation</span><span class="token operator">/</span><span class="token maybe-class-name">Splunk</span>
<span class="token maybe-class-name">The</span> <span class="token maybe-class-name">Splunk</span> web <span class="token keyword">interface</span> <span class="token class-name">is</span> at http<span class="token operator">:</span><span class="token operator">/</span><span class="token operator">/</span>localhost<span class="token operator">:</span><span class="token number">8000</span><span aria-hidden="true" class="line-numbers-rows"><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span></span></code></pre>

#### Links Importantes
- [Exploring Splunk](http://www.splunk.com/goto/book)
- [Documentação do Splunk](http://docs.splunk.com/Documentation)
- [Download do arquivo de logs (Sampledata.zip)](http://tinyurl.com/bgmkod3)
- [Site oficial Splunk em português](http://pt.splunk.com)
- [Splunk Processing Language Book](http://www.splunk.com/goto/book)


