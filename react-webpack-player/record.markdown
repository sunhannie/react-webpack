createClass声明组件的方式
动态替换里面的内容，不是刷新，只是更新修改的内容
html-webpack-plugin不用链接最终的打包文件
jquery:基于事件的驱动，比如用户点击的button，是触发一个事件，根据事件操作ui
react：关心数据驱动，ui上不需要管，react会帮我们处理
react中数据分为2种：state和props
jsx必须包裹在一个元素里
jplayer
<!-- <script type="text/javascript" src="dist/bundle.js"></script> 不关心链接打包文件-->
<!-- react生命周期 -->
绑定时间需要记住解绑,解绑增加健壮性
不能这么注释在progress.js：// {this.props.progress}s
es6语法，模板字符串语法
组件中通讯？
函数应该先检查函数是否存在，再调用。
用户想更改进度条颜色怎么办？
background:#2f9842;
root仅仅进行页面的管理，把之前的player逻辑分离到player.js中
从网上获取接口？
<Player currentMusicItem={this.state.currentMusicItem}></Player>

focus={item === this.props.currentMusicItem} 
// <li className={`components-musiclistitem row${this.props.focus ? ' focus' : ''}`} >

	return ( 
				<li>
				<MusicListItem
				key={item.id}
				musicItem={item}>
				{item.title}
				</MusicListItem>
			</li>
				);
			括号不能少

			react-router
			

			注册个人信息
