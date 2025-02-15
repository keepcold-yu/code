# 环境信息
- **MindSpore版本**: `2.4.10`
- **CANN版本**: `8.0`
- **设备**: `Ascend`


# 测试样例
- **单张图片预测**
```python
python predict.py --model xxx.ckpt --input 1.png --soc 310
```
- **批量预测**
```python
python predict.py --model xxx.ckpt --input test/ --batch_size 16 --soc 310
```
