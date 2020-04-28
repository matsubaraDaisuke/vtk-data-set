# my vtk(Python)記事のまとめ



# 環境構築

``` terminal:terminal 
$ pip install vtk
```

# reader
- [OpenFOAMReader](https://qiita.com/matsubaradaisuke/items/2035a779ffc383820ad3) :OpenFOAM形式の読み込み
- [vtkXMLUnstructuredGridReader](https://qiita.com/matsubaradaisuke/items/0876c9c3225e520a8f38):vtu形式の読み込み

# filter
- [vtkThreshold](https://qiita.com/matsubaradaisuke/items/c29be9bdd115bc4d144f):指定した範囲内の値を含む要素のみ抽出するフィルター

# writer
- [vtkSTLWriter](https://qiita.com/matsubaradaisuke/items/91518c9c86dc6f42c47c):stlの出力
- [vtkPolyDataWriter](https://qiita.com/matsubaradaisuke/items/91518c9c86dc6f42c47c):vtkの出力
- [vtkPLYWriter](https://qiita.com/matsubaradaisuke/items/91518c9c86dc6f42c47c):plyの出力
