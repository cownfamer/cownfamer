<!DOCTYPE html>
<html>
<head>
    <title>Đăng ký tài khoản</title>
    <meta charset="UTF8" > 
</head>
    <body>
		<h1 text-align: center; style = color:blue;>Đăng ký tài khoản</h1>
		<hr>
            <caption></caption>
            <table>
                <tr>
                    <th>Họ tên(*)</th>
                    <td><input type="text" placeholder="Họ tên" style = "width: 350px; height: 30px;"></td>
                </tr>
                <tr>
                    <th>Email(*)</th>
                    <td><input type="text" placeholder="Email" style = "width: 350px; height: 30px;"></td>
                </tr>
                <tr>
                    <th>Số điện thoại</th>
                    <td> <input type = tol name = ' telTelephone' placeholder = 'Số điện thoại'pattern= "[0]{1}[0-9]{1}[0-9]{8}" style = "width: 350px; height: 30px;"></td>
                </tr>
                <tr>
                    <th>Tỉnh Thành</th>
                    <td>
                        <select style=" height: 30px;
                        width: 358px;">
                            <option>Bình Dương</option>
                            <option>Thái Bình</option>
                            <option>Hà Nội</option>
                            <option>Nam Định</option>
                            <option>Hải Dương</option>
                            <option>Quảng Ninh</option>
                            <option>Hà Nội</option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <th>Mật Khẩu(*)</th>
                    <td><input type="password" placeholder="Mật Khẩu" style = "width: 350px; height: 30px;"></td>
                </tr>
                <tr>
                    <th>Xác nhận mật khẩu mới(*)</th>
                    <td><input type="password" placeholder="Xác nhận mật khẩu mới" style = "width: 350px; height: 30px;"></td>
                </tr>
                <tr>
                    <th>Mã xác nhận</th>
                    <td><input type="text" style = "width: 350px; height: 30px;"></td>
                    <td><img src="https://media.discordapp.net/attachments/848090548564787204/886936567418077224/unknown.png" alt=""></td>
                </tr>
                <tr>
                    <th></th>
                    <td><input type="submit" value="Đăng kí" style = "color:white; background-color: #6699CC;"></td>
                </tr>
            </table>
        </form> <hr> <p> Nếu bạn đã có tài khoản | <a href="#" style="text-decoration: none; color: darkcyan;"> Đăng nhập </a> </p>
    </body>
</html>
