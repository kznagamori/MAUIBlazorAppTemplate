# MAUIBlazorAppTemplate
MAUI Blazor アプリを作成するためのテンプレート

## 使用法

### テンプレートの取得
[MAUIBlazorApp.nupkg](https://github.com/kznagamori/MAUIBlazorAppTemplate/releases/download/v1.0.0/kznagamori.MAUIBlazorApp.1.0.0.nupkg)
をダウンロードします。

### テンプレートのインストール
ダウンロードしたnugetパッケージをインストールします。
```
dotnet new install kznagamori.MAUIBlazorApp.1.0.0.nupkg
```

### MAUI Blazor アプリプロジェクトの作成
```
 dotnet new  maui-blazor.app -n <プロジェクト名>
```
**例:** `dotnet new maui-blazor.app -n MyMauiXPlat`

### テンプレートのアンインストール
```
dotnet new  uninstall kznagamori.MAUIBlazorApp
```

### ターゲット

net8.0のみをターゲットとしています。

### ビルド

```
dotnet build
```

### リリースビルド

```
publish_windows.bat
```

### kznagamori.MAUIBlazorApp.X.X.X.nupkgの作成

```
nuget pack .\MAUIBlazorAppTemplate.nuspec
```

