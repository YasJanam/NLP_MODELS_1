# transformer_vs_conv1d
در این کد میخواهیم قبل و بعد از کانولوشن یک بعدی ( وقتی بعد از ترنسفورمر قرار داده میشود) را بررسی کنیم.

خلاصه کاری که میخواهیم بکنیم این است گذاشتن یک لایه کانولوشن روی ترنسفورمر چه تفاوتی روی داده ها  ایجاد میکند

در این کد شبکه عصبی استفاده شده بسیار ساده است : 2 لایه ترنسفورمر + 1 لایه کانولوشن

### خلاصه کلی

transformerLayer -> transformerLayer -> __output_befor_conv__ -> Conv1D -> __output_after_conv__

مقایسه میکنیم __tsne__ را با کمک output_after_conv , output_befor_conv سپس 

موجود است pdf نتیجه ویژوالایز شده ی مقایسه در 

###  عکس نتیجه مقایسه در یک اجرا : 
<img width="824" height="565" alt="image" src="https://github.com/user-attachments/assets/fc26e6a9-8c57-4cc3-a441-418cf9ce7dd5" />
