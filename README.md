# Kubernetes Operator built with Ansible Example

[![Docker Repository on Quay](https://quay.io/repository/imokuri/imo-operator/status "Docker Repository on Quay")](https://quay.io/repository/imokuri/imo-operator)

## CustomResource

### Kind: Imo

nginxが起動するDeploymentとServiceが作成されます。

### Kind: Kuri

10秒スリープするだけのJobが30秒おきに動きます。

### Kind: Kabocha

(Imoで起動したnginxにアクセスして、)customのstatusをセットします。

### Kind: KatsuDon

ImoとKuriとKabochaを起動します。

## ToDo

- moleculeでのテスト
- imageの自動ビルド
