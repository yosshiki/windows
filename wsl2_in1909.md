KB4566116の確認  
設定＞更新とセキュリティ＞Windows Update＞更新の履歴を表示する  

cmd  
>wsl -l -v  
  NAME            STATE           VERSION  
* Ubuntu-20.04    Running         1  

>wsl.exe --set-default-version 2
Windows の仮想マシン プラットフォーム機能を有効にして、BIOS で仮想化が有効になっていることを確認してください。  
詳細については、https://aka.ms/wsl2-install を参照してください  

