## 于骏最牛逼

<!DOCTYPE html>
<html lang="en">
<head>
	<meta http-equiv="X-UA-Compatible" Content="IE=edge,chrome=1"/>
    <meta http-equiv="Content-Language" Content="zh-CN"/>
    <meta charset="UTF-8"/>
    <meta name="keyword" content="跟单"/>
    <meta name="description" content="跟单超人--自由跟单，从此开始"/>
	<title>用户登录</title>
	<link rel="icon" href="img/icon.ico" />
    <link rel="stylesheet" href="css/common.css" /><!-- 公共样式 -->
    <link rel="stylesheet" href="css/login.css" />
</head>
<body>
	<section id="section">
		
		<div class="form_box">
			
			<div class="form_title">
				<img src="img/login_title.png" alt="">
			</div>
			<div class="web_tips">（本网站暂时只支持派单功能）</div>
			<div class="form_content">
				<form action="" class="form_section" id="loginForm">
					<div class="form_bar">
						<img src="img/login_bar.png" alt="">
					</div>
					<div class="form_input phone_input">
						<span class="icon"></span>
						<span class="tips">请输入手机号</span>
						<input type="text" name="phone" class="txt_input">
					</div>
					<div class="form_input code_input">
						<span class="icon"></span>
						<span class="tips">请输入验证码</span>
						<input type="text" name="veri_code" class="txt_input">
						<span type="text" class="get_code" >获取验证码</span>
						<!-- <a href="###" class="get_code">获取验证码</a> -->
					</div>
					<a href="###" class=" btn  login_btn blue_btn">登录</a>
				</form>
			</div>
		</div>
	</section>

	<!-- 提示弹窗 -->
	<div class="alert_popup tips_popup">
		<span class="alert_icon"></span>
		<span class="alert_msg"></span>
	</div>
	<!-- end提示弹窗 -->
	<!-- 提交成功弹窗 -->
	<div class="modal succ_popup_modal">
		<div class="alert_popup succ_popup">
			<span class="alert_msg">提交成功，我们会尽快联系您</span>
		</div>
	</div>
	
	<!-- end提交成功弹窗 -->

	<!-- 用户不存在弹窗 -->
	<div class="modal inexistence_modal">
		<div class="modal_container">
			<div class="modal_content">
				<span class="modal_close"></span>
				<div class="modal_head">抱歉，您还不是跟单超人的用户！</div>
				<div class="modal_body">
					<p>如果您是公司员工，请联系老板为您添加角色信息；</p>
					<p>如果您是外贸公司老板，想要更好的管理公司跟单，请联系我们申请使用“跟单超人”</p>
				</div>
				<div class="modal_foot">
					<a href="###" class="btn modal_btn blue_btn applyUse">申请使用</a>
				</div>
			</div>
		</div>
	</div>
	<!-- end用户不存在弹窗 -->

	<!-- 申请使用弹窗 -->
	<div class="modal applyUse_modal">
		<div class="modal_container">
			<div class="modal_content">
				<span class="modal_close"></span>
				<div class="modal_head">方便我们联系您</div>
				<div class="modal_body">
					<ul class="form_section" id="applyForm">
						<li class="company_item">
							<span class="apply_icon"></span>
							<span class="apply_tips tips">公司名</span>
							<input type="text" name="company">
						</li>
						<li class="name_item">
							<span class="apply_icon"></span>
							<span class="apply_tips tips">姓名</span>
							<input type="text" name="name">
						</li>
						<li class="position_item">
							<span class="apply_icon"></span>
							<span class="apply_tips tips">职位</span>
							<input type="text" name="position">
						</li>
						<li class="phone_item">
							<span class="apply_icon"></span>
							<span class="apply_tips tips">手机号</span>
							<input type="text" name="phone">
						</li>
						<li class="remark_item">
							<span class="apply_icon"></span>
							<span class="apply_tips tips">备注</span>
							<input type="text" name="remark">
						</li> 
					</ul>
				</div>
				<div class="modal_foot">
					<a href="###" class="btn modal_btn applySubmit blue_btn">提交</a>
				</div>
			</div>
		</div>
	</div>
	<!-- end申请使用弹窗 -->

	<script type="text/javascript" src="js/plugins/jquery.min.js"></script>
	<script type="text/javascript" src="js/plugins/jquery.particleground.min.js"></script><!-- 背景图插件 -->
	<script type="text/javascript" src="js/common.js"></script>
	<script type="text/javascript" src="js/login.js"></script>
</body>
</html>
