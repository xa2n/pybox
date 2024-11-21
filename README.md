# pybox
### **仮想環境を作成**

プロジェクトディレクトリに移動し、以下を実行して仮想環境を作成します：

```bash
uv venv

```

これにより、`.venv`フォルダが作成されます。

### **仮想環境を有効化**

以下のコマンドで仮想環境を有効化します：

```bash
source .venv/bin/activate

```

---

### **4. データ分析/機械学習用パッケージのインストール**

### **必要なライブラリをインストール**

以下は一般的なデータ分析や機械学習に必要なライブラリです：

```bash
uv add pandas numpy matplotlib seaborn scikit-learn jupyter keras tensorflow

```

---

### **5. Jupyter Notebook環境の設定**

### **Jupyter Notebookファイルの作成**

1. VSCode内で新しいファイルを作成し、`notebook.ipynb`として保存。
2. Command Palette（`Shift+Cmd+P`）で「Create: New Jupyter Notebook」を選択。

### **カーネルを選択**

ノートブック右上から、先ほど作成した仮想環境（`.venv`）をカーネルとして選択します。

---

## **補足情報とベストプラクティス**

- `uv`は依存関係管理が容易で、高速に動作するため、特にプロジェクトが複雑化した際に便利です。
- プロジェクトごとに依存関係を明確にするため、`requirements.txt`や`pyproject.toml`ファイルを活用しましょう。
- VSCodeでは、Jupyter Notebookやデバッグツールが統合されているため、効率的に開発できます。
