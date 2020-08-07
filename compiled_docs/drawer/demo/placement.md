{"title":"自定义弹出方向","meta":{"title":"自定义弹出方向","description":"\n<p>自定义弹出方向</p>\n","order":"1"},"codes":{"jsx":"import { Radio, Button, Drawer } from '@alifd/next';\n\nclass Demo extends React.Component {\n    state = {\n        visible: false,\n        placement: 'right'\n    };\n\n    onOpen = () => {\n        this.setState({\n            visible: true\n        });\n    };\n\n    onClose = (reason) => {\n\n        this.setState({\n            visible: false\n        });\n    };\n\n    onPlacementChange = dir => {\n        this.setState({\n            placement: dir\n        });\n    }\n\n    render() {\n        return (\n            <div>\n                <Radio.Group\n                    dataSource={['right', 'bottom', 'left', 'top']}\n                    defaultValue={'right'}\n                    onChange={this.onPlacementChange}\n                /> &nbsp;&nbsp;&nbsp;&nbsp;\n                <Button type=\"primary\" onClick={this.onOpen}> open </Button>\n                <Drawer\n                    title=\"标题\"\n                    visible={this.state.visible}\n                    placement={this.state.placement}\n                    onClose={this.onClose}>\n                    Start your business here by searching a popular product\n                </Drawer>\n            </div>\n        );\n    }\n}\n\nReactDOM.render(<Demo />, mountNode);\n"},"body":"\n\n````jsx\nimport { Radio, Button, Drawer } from '@alifd/next';\n\nclass Demo extends React.Component {\n    state = {\n        visible: false,\n        placement: 'right'\n    };\n\n    onOpen = () => {\n        this.setState({\n            visible: true\n        });\n    };\n\n    onClose = (reason) => {\n\n        this.setState({\n            visible: false\n        });\n    };\n\n    onPlacementChange = dir => {\n        this.setState({\n            placement: dir\n        });\n    }\n\n    render() {\n        return (\n            <div>\n                <Radio.Group\n                    dataSource={['right', 'bottom', 'left', 'top']}\n                    defaultValue={'right'}\n                    onChange={this.onPlacementChange}\n                /> &nbsp;&nbsp;&nbsp;&nbsp;\n                <Button type=\"primary\" onClick={this.onOpen}> open </Button>\n                <Drawer\n                    title=\"标题\"\n                    visible={this.state.visible}\n                    placement={this.state.placement}\n                    onClose={this.onClose}>\n                    Start your business here by searching a popular product\n                </Drawer>\n            </div>\n        );\n    }\n}\n\nReactDOM.render(<Demo />, mountNode);\n````","html":"<script>(function(){'use strict';\n\nvar _createClass = function () { function defineProperties(target, props) { for (var i = 0; i < props.length; i++) { var descriptor = props[i]; descriptor.enumerable = descriptor.enumerable || false; descriptor.configurable = true; if (\"value\" in descriptor) descriptor.writable = true; Object.defineProperty(target, descriptor.key, descriptor); } } return function (Constructor, protoProps, staticProps) { if (protoProps) defineProperties(Constructor.prototype, protoProps); if (staticProps) defineProperties(Constructor, staticProps); return Constructor; }; }();\n\nvar _next = require('@alifd/next');\n\nfunction _classCallCheck(instance, Constructor) { if (!(instance instanceof Constructor)) { throw new TypeError(\"Cannot call a class as a function\"); } }\n\nfunction _possibleConstructorReturn(self, call) { if (!self) { throw new ReferenceError(\"this hasn't been initialised - super() hasn't been called\"); } return call && (typeof call === \"object\" || typeof call === \"function\") ? call : self; }\n\nfunction _inherits(subClass, superClass) { if (typeof superClass !== \"function\" && superClass !== null) { throw new TypeError(\"Super expression must either be null or a function, not \" + typeof superClass); } subClass.prototype = Object.create(superClass && superClass.prototype, { constructor: { value: subClass, enumerable: false, writable: true, configurable: true } }); if (superClass) Object.setPrototypeOf ? Object.setPrototypeOf(subClass, superClass) : subClass.__proto__ = superClass; }\n\nvar Demo = function (_React$Component) {\n    _inherits(Demo, _React$Component);\n\n    function Demo() {\n        var _ref;\n\n        var _temp, _this, _ret;\n\n        _classCallCheck(this, Demo);\n\n        for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {\n            args[_key] = arguments[_key];\n        }\n\n        return _ret = (_temp = (_this = _possibleConstructorReturn(this, (_ref = Demo.__proto__ || Object.getPrototypeOf(Demo)).call.apply(_ref, [this].concat(args))), _this), _this.state = {\n            visible: false,\n            placement: 'right'\n        }, _this.onOpen = function () {\n            _this.setState({\n                visible: true\n            });\n        }, _this.onClose = function (reason) {\n\n            _this.setState({\n                visible: false\n            });\n        }, _this.onPlacementChange = function (dir) {\n            _this.setState({\n                placement: dir\n            });\n        }, _temp), _possibleConstructorReturn(_this, _ret);\n    }\n\n    _createClass(Demo, [{\n        key: 'render',\n        value: function render() {\n            return React.createElement(\n                'div',\n                null,\n                React.createElement(_next.Radio.Group, {\n                    dataSource: ['right', 'bottom', 'left', 'top'],\n                    defaultValue: 'right',\n                    onChange: this.onPlacementChange\n                }),\n                ' \\xA0\\xA0\\xA0\\xA0',\n                React.createElement(\n                    _next.Button,\n                    { type: 'primary', onClick: this.onOpen },\n                    ' open '\n                ),\n                React.createElement(\n                    _next.Drawer,\n                    {\n                        title: '\\u6807\\u9898',\n                        visible: this.state.visible,\n                        placement: this.state.placement,\n                        onClose: this.onClose },\n                    'Start your business here by searching a popular product'\n                )\n            );\n        }\n    }]);\n\n    return Demo;\n}(React.Component);\n\nReactDOM.render(React.createElement(Demo, null), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Radio<span class=\"token punctuation\">,</span> Button<span class=\"token punctuation\">,</span> Drawer <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">class</span> <span class=\"token class-name\">Demo</span> <span class=\"token keyword\">extends</span> <span class=\"token class-name\">React<span class=\"token punctuation\">.</span>Component</span> <span class=\"token punctuation\">{</span>\n    state <span class=\"token operator\">=</span> <span class=\"token punctuation\">{</span>\n        visible<span class=\"token operator\">:</span> <span class=\"token boolean\">false</span><span class=\"token punctuation\">,</span>\n        placement<span class=\"token operator\">:</span> <span class=\"token string\">'right'</span>\n    <span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\n    <span class=\"token function-variable function\">onOpen</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n        <span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span><span class=\"token function\">setState</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">{</span>\n            visible<span class=\"token operator\">:</span> <span class=\"token boolean\">true</span>\n        <span class=\"token punctuation\">}</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n    <span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\n    <span class=\"token function-variable function\">onClose</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token parameter\">reason</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n\n        <span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span><span class=\"token function\">setState</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">{</span>\n            visible<span class=\"token operator\">:</span> <span class=\"token boolean\">false</span>\n        <span class=\"token punctuation\">}</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n    <span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\n    <span class=\"token function-variable function\">onPlacementChange</span> <span class=\"token operator\">=</span> <span class=\"token parameter\">dir</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n        <span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span><span class=\"token function\">setState</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">{</span>\n            placement<span class=\"token operator\">:</span> dir\n        <span class=\"token punctuation\">}</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n    <span class=\"token punctuation\">}</span>\n\n    <span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token punctuation\">{</span>\n        <span class=\"token keyword\">return</span> <span class=\"token punctuation\">(</span>\n            <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Radio.Group</span></span>\n                    <span class=\"token attr-name\">dataSource</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">[</span><span class=\"token string\">'right'</span><span class=\"token punctuation\">,</span> <span class=\"token string\">'bottom'</span><span class=\"token punctuation\">,</span> <span class=\"token string\">'left'</span><span class=\"token punctuation\">,</span> <span class=\"token string\">'top'</span><span class=\"token punctuation\">]</span><span class=\"token punctuation\">}</span></span>\n                    <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token string\">'right'</span><span class=\"token punctuation\">}</span></span>\n                    <span class=\"token attr-name\">onChange</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span>onPlacementChange<span class=\"token punctuation\">}</span></span>\n                <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\"> &amp;nbsp;&amp;nbsp;&amp;nbsp;&amp;nbsp;\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Button</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">onClick</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span>onOpen<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\"> open </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Button</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Drawer</span></span>\n                    <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>标题<span class=\"token punctuation\">\"</span></span>\n                    <span class=\"token attr-name\">visible</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span>state<span class=\"token punctuation\">.</span>visible<span class=\"token punctuation\">}</span></span>\n                    <span class=\"token attr-name\">placement</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span>state<span class=\"token punctuation\">.</span>placement<span class=\"token punctuation\">}</span></span>\n                    <span class=\"token attr-name\">onClose</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token keyword\">this</span><span class=\"token punctuation\">.</span>onClose<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n                    Start your business here by searching a popular product\n                </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Drawer</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span>\n        <span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n    <span class=\"token punctuation\">}</span>\n<span class=\"token punctuation\">}</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Demo</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}