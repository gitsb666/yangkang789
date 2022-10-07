
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>注册页面</title>
	</head>
	<body>
		<table width="520" height="450">
			<tr>
				<td>姓名：</td>
				<td>
					<input type="text" name="name" value="   " />
				</td>
			</tr>
			<tr>
				<td>年龄：</td>
				<td>
					<input type="text" name="age" value="    " />
				</td>
			</tr>
			<tr>
				<td>性别：</td>
				<td>
					<input type="radio" name="sex" id="boy" />
					<label for="boy"><img src="man.png" width="15" height="15" />男</label>
					<input type="radio" name="sex" id="girl" />
					<label for="girl"><img src="girl.png" width="15" height="15" />女</label>
				</td>
			</tr>
			<tr>
				<td>出生日期：</td>
				<td>
						<input type="text" name="age" value="    " />
				</td>
			</tr>
			<tr>
				<td>Email：</td>
				<td>
						<input type="text" name="age" value="     " />
				</td>
			</tr>
			<tr>
				<td>个人主页：</td>
				<td>
						<input type="text" name="age" value="  " />
				</td>
			</tr>
			<tr>
				<td>个人简介：</td>
			</tr>
			<tr>
				<td colspan="2"><textarea rows="6" cols="50">请输入你的个人简介....</textarea></td>
			</tr>
			<tr>
				<td align="center" colspan="2"><input type="checkbox" name="agree" id="f" checked /><label
						for="f">同意信息录入</label></td>
			</tr>
			<tr>
				<td align="center" colspan="2">
					<input type="submit" value="立即注册" />
					<input type="reset" value="取消" />
				</td>
			</tr>
		</table>
	</body>
</html>
