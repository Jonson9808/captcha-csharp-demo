# ��ʾ˵��

* ��captcha-csharp-demo.sln
* �Ҽ������������ԭNuGet��
* ���� Views\Login\Index.cshtml �ļ�
```
"captchaId": "YOUR_CAPTCHA_ID", // �����������뵽����֤��id
```

* ���� Controllers\LoginController.cs �ļ���������׶ܹ������뵽��������Ϣ
```
	private static string captchaId = "YOUR_CAPTCHA_ID"; // ��֤��id
	private static string secretId = "YOUR_SECRET_ID"; // ��Կ��id
	private static string secretKey = "YOUR_SECRET_KEY"; // ��Կ��key
```

* ������ʾ����