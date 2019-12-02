{"meta":"<h2 id=\"&#x5F00;&#x53D1;&#x6307;&#x5357;\">&#x5F00;&#x53D1;&#x6307;&#x5357;<a href=\"#&#x5F00;&#x53D1;&#x6307;&#x5357;\" class=\"anchor\">#</a></h2><h3 id=\"&#x4F55;&#x65F6;&#x4F7F;&#x7528;\">&#x4F55;&#x65F6;&#x4F7F;&#x7528;<a href=\"#&#x4F55;&#x65F6;&#x4F7F;&#x7528;\" class=\"anchor\">#</a></h3><p>&#x6570;&#x5B57;&#x9009;&#x62E9;&#x5668;&#xFF0C;&#x5E76;&#x5BF9;&#x8F93;&#x5165;&#x7684;&#x6570;&#x636E;&#x505A;&#x6B63;&#x786E;&#x6027;&#x68C0;&#x67E5;&#x3001;&#x81EA;&#x52A8;&#x8BA2;&#x6B63;&#x3002;</p>\n<h3 id=\"&#x6CE8;&#x610F;&#x4E8B;&#x9879;\">&#x6CE8;&#x610F;&#x4E8B;&#x9879;<a href=\"#&#x6CE8;&#x610F;&#x4E8B;&#x9879;\" class=\"anchor\">#</a></h3><ol>\n<li><p>&#x81EA;&#x52A8;&#x8BA2;&#x6B63;&#x53EF;&#x80FD;&#x4F1A;&#x5BFC;&#x81F4;onChange&#x8FD4;&#x56DE;&#x503C;&#x548C;&#x4F60;&#x8F93;&#x5165;&#x7684;&#x6570;&#x636E;&#x4E0D;&#x4E00;&#x6837;&#x3002;</p>\n</li>\n<li><p>&#x5176;&#x4E2D;&#x6709;&#x4E9B;&#x4E2D;&#x95F4;&#x8F93;&#x5165;&#x72B6;&#x6001;&#x65E0;&#x6CD5;&#x89E6;&#x53D1;onChange&#xFF0C;&#x4E3B;&#x8981;&#x8003;&#x8651;&#x5230;&#x81EA;&#x52A8;&#x8BA2;&#x6B63;&#x53EF;&#x80FD;&#x6C38;&#x8FDC;&#x65E0;&#x6CD5;&#x5230;&#x8FBE;&#x60F3;&#x8981;&#x7684;&#x503C;&#x4E86;&#x3002;&#x4F8B;&#x5982;&#xFF1A;</p>\n<ul>\n<li><code>0</code>=&gt;<code>0.</code>=&gt;<code>0.0</code>=&gt;<code>0.01</code>  &#x4E2D;&#x95F4;&#x4E24;&#x6B65;&#x4E0D;&#x4F1A;&#x89E6;&#x53D1;onChange&#xFF0C;&#x56E0;&#x4E3A;&#x5982;&#x679C;&#x8BA2;&#x6B63;&#x4F1A;&#x4E00;&#x76F4;&#x505C;&#x7559;&#x5728;0&#x5BFC;&#x81F4;&#x6C38;&#x8FDC;&#x65E0;&#x6CD5;&#x5230;&#x8FBE;&#x60F3;&#x8981;&#x7684;&#x503C;</li>\n<li>min=10 &#x7684;&#x60C5;&#x51B5;&#x4E0B;, &#x8F93;&#x5165; <code>1</code>=&gt;<code>12</code>  &#x7B2C;&#x4E00;&#x6B65; <code>1</code> &#x4E0D;&#x4F1A;&#x89E6;&#x53D1;onChange&#x4E5F;&#x4E0D;&#x4F1A;&#x8BA2;&#x6B63;&#x6570;&#x636E;&#xFF0C;&#x56E0;&#x4E3A;&#x6570;&#x5B57;&#x662F;&#x4E00;&#x4E2A;&#x4E00;&#x4E2A;&#x8F93;&#x5165;&#x7684;</li>\n</ul>\n</li>\n<li><p>&#x5982;&#x679C;&#x8F93;&#x5165;&#x65F6;&#x6CA1;&#x89E6;&#x53D1;onChange&#xFF0C;&#x4F1A;&#x5728;onBlur&#x68C0;&#x6D4B;&#x6570;&#x636E;&#x6B63;&#x786E;&#x6027;&#x5E76;&#x89E6;&#x53D1;onChange</p>\n</li>\n</ol>\n<h2 id=\"api\">API<a href=\"#api\" class=\"anchor\">#</a></h2>","api":"<h3 id=\"numberpicker\">NumberPicker<a href=\"#numberpicker\" class=\"anchor\">#</a></h3><table>\n<thead>\n<tr>\n<th>&#x53C2;&#x6570;</th>\n<th>&#x8BF4;&#x660E;</th>\n<th>&#x7C7B;&#x578B;</th>\n<th>&#x9ED8;&#x8BA4;&#x503C;</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td>size</td>\n<td>&#x5927;&#x5C0F;<br><br><strong>&#x53EF;&#x9009;&#x503C;</strong>:<br>&apos;large&apos;, &apos;medium&apos;</td>\n<td>Enum</td>\n<td>&apos;medium&apos;</td>\n</tr>\n<tr>\n<td>type</td>\n<td>&#x8BBE;&#x7F6E;&#x7C7B;&#x578B;<br><br><strong>&#x53EF;&#x9009;&#x503C;</strong>:<br>&apos;normal&apos;(&#x666E;&#x901A;)<br>&apos;inline&apos;(&#x5185;&#x8054;)</td>\n<td>Enum</td>\n<td>&apos;normal&apos;</td>\n</tr>\n<tr>\n<td>value</td>\n<td>&#x5F53;&#x524D;&#x503C;</td>\n<td>Number</td>\n<td>-</td>\n</tr>\n<tr>\n<td>defaultValue</td>\n<td>&#x9ED8;&#x8BA4;&#x503C;</td>\n<td>Number</td>\n<td>-</td>\n</tr>\n<tr>\n<td>disabled</td>\n<td>&#x662F;&#x5426;&#x7981;&#x7528;</td>\n<td>Boolean</td>\n<td>-</td>\n</tr>\n<tr>\n<td>step</td>\n<td>&#x6B65;&#x957F;</td>\n<td>Number/String</td>\n<td>1</td>\n</tr>\n<tr>\n<td>precision</td>\n<td>&#x4FDD;&#x7559;&#x5C0F;&#x6570;&#x70B9;&#x540E;&#x4F4D;&#x6570;</td>\n<td>Number</td>\n<td>0</td>\n</tr>\n<tr>\n<td>editable</td>\n<td>&#x7528;&#x6237;&#x662F;&#x5426;&#x53EF;&#x4EE5;&#x8F93;&#x5165;</td>\n<td>Boolean</td>\n<td>true</td>\n</tr>\n<tr>\n<td>autoFocus</td>\n<td>&#x81EA;&#x52A8;&#x7126;&#x70B9;</td>\n<td>Boolean</td>\n<td>-</td>\n</tr>\n<tr>\n<td>onChange</td>\n<td>&#x6570;&#x503C;&#x88AB;&#x6539;&#x53D8;&#x7684;&#x4E8B;&#x4EF6;<br><br><strong>&#x7B7E;&#x540D;</strong>:<br>Function(value: Number, e: Event) =&gt; void<br><strong>&#x53C2;&#x6570;</strong>:<br><em>value</em>: {Number} &#x6570;&#x636E;<br>_e_: {Event} DOM&#x4E8B;&#x4EF6;&#x5BF9;&#x8C61;</td>\n<td>Function</td>\n<td>func.noop</td>\n</tr>\n<tr>\n<td>onKeyDown</td>\n<td>&#x952E;&#x76D8;&#x6309;&#x4E0B;<br><br><strong>&#x7B7E;&#x540D;</strong>:<br>Function() =&gt; void</td>\n<td>Function</td>\n<td>func.noop</td>\n</tr>\n<tr>\n<td>onFocus</td>\n<td>&#x7126;&#x70B9;&#x83B7;&#x5F97;<br><br><strong>&#x7B7E;&#x540D;</strong>:<br>Function() =&gt; void</td>\n<td>Function</td>\n<td>-</td>\n</tr>\n<tr>\n<td>onBlur</td>\n<td>&#x7126;&#x70B9;&#x5931;&#x53BB;<br><br><strong>&#x7B7E;&#x540D;</strong>:<br>Function() =&gt; void</td>\n<td>Function</td>\n<td>func.noop</td>\n</tr>\n<tr>\n<td>onCorrect</td>\n<td>&#x6570;&#x503C;&#x8BA2;&#x6B63;&#x540E;&#x7684;&#x56DE;&#x8C03;<br><br><strong>&#x7B7E;&#x540D;</strong>:<br>Function(obj: Object) =&gt; void<br><strong>&#x53C2;&#x6570;</strong>:<br><em>obj</em>: {Object} {currentValue,oldValue:String}</td>\n<td>Function</td>\n<td>func.noop</td>\n</tr>\n<tr>\n<td>max</td>\n<td>&#x6700;&#x5927;&#x503C;</td>\n<td>Number</td>\n<td>Infinity</td>\n</tr>\n<tr>\n<td>min</td>\n<td>&#x6700;&#x5C0F;&#x503C;</td>\n<td>Number</td>\n<td>-Infinity</td>\n</tr>\n<tr>\n<td>format</td>\n<td>&#x683C;&#x5F0F;&#x5316;&#x5F53;&#x524D;&#x503C;<br><br><strong>&#x7B7E;&#x540D;</strong>:<br>Function(value: Number) =&gt; String/Number<br><strong>&#x53C2;&#x6570;</strong>:<br><em>value</em>: {Number} null<br><strong>&#x8FD4;&#x56DE;&#x503C;</strong>:<br>{String/Number} null<br></td>\n<td>Function</td>\n<td>-</td>\n</tr>\n<tr>\n<td>upBtnProps</td>\n<td>&#x589E;&#x52A0;&#x6309;&#x94AE;&#x7684;props</td>\n<td>Object</td>\n<td>-</td>\n</tr>\n<tr>\n<td>downBtnProps</td>\n<td>&#x51CF;&#x5C11;&#x6309;&#x94AE;&#x7684;props</td>\n<td>Object</td>\n<td>-</td>\n</tr>\n<tr>\n<td>label</td>\n<td>&#x5185;&#x8054; label</td>\n<td>ReactNode</td>\n<td>-</td>\n</tr>\n<tr>\n<td>innerAfter</td>\n<td>inner after</td>\n<td>ReactNode</td>\n<td>-</td>\n</tr>\n<tr>\n<td>isPreview</td>\n<td>&#x662F;&#x5426;&#x4E3A;&#x9884;&#x89C8;&#x6001;</td>\n<td>Boolean</td>\n<td>-</td>\n</tr>\n<tr>\n<td>renderPreview</td>\n<td>&#x9884;&#x89C8;&#x6001;&#x6A21;&#x5F0F;&#x4E0B;&#x6E32;&#x67D3;&#x7684;&#x5185;&#x5BB9;<br><br><strong>&#x7B7E;&#x540D;</strong>:<br>Function(value: number) =&gt; void<br><strong>&#x53C2;&#x6570;</strong>:<br><em>value</em>: {number} &#x8BC4;&#x5206;&#x503C;</td>\n<td>Function</td>\n<td>-</td>\n</tr>\n<tr>\n<td>device</td>\n<td>&#x9884;&#x8BBE;&#x5C4F;&#x5E55;&#x5BBD;&#x5EA6;<br><br><strong>&#x53EF;&#x9009;&#x503C;</strong>:<br>&apos;phone&apos;, &apos;tablet&apos;, &apos;desktop&apos;</td>\n<td>Enum</td>\n<td>-</td>\n</tr>\n</tbody>\n</table>\n<h2 id=\"aria-and-keyboard\">ARIA and KeyBoard<a href=\"#aria-and-keyboard\" class=\"anchor\">#</a></h2><table>\n<thead>\n<tr>\n<th style=\"text-align:left\">&#x6309;&#x952E;</th>\n<th style=\"text-align:left\">&#x8BF4;&#x660E;</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td style=\"text-align:left\">Up Arrow</td>\n<td style=\"text-align:left\">&#x6570;&#x5B57;&#x589E;&#x52A0;</td>\n</tr>\n<tr>\n<td style=\"text-align:left\">Down Arrow</td>\n<td style=\"text-align:left\">&#x6570;&#x5B57;&#x51CF;&#x5C0F;</td>\n</tr>\n</tbody>\n</table>\n"}