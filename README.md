# FlowNet-2

## Built With

* [Python](https://www.python.org/).
* [Colab](https://colab.research.google.com/).
* [FlowNet2](https://drive.google.com/file/d/1hF8vS6YeHkx3j2pfCeQqqZGwA_PJq_Da/view).
* [PyTorch==1.4.0](https://pytorch.org/)
* [Scipy](https://docs.scipy.org/doc/scipy/).

## Generate .flo files using FlowNet2
```Python
!python main.py --inference --model FlowNet2 --save_flow --save ./output --inference_dataset ImagesFromFolder --inference_dataset_root ./frames/ --resume ./Flow.tar
```

## Results 
### Original vidio
https://user-images.githubusercontent.com/71349228/211192670-32ddc69a-6824-46bd-af64-df9200d73d93.mp4

### Output vidio
https://user-images.githubusercontent.com/71349228/211192688-91f882a3-db90-4316-a924-001ffa61ca16.mp4

### .flo file 
 
https://user-images.githubusercontent.com/71349228/211192702-97652cf4-082d-4d25-b674-a9fd5558701b.mp4











https://user-images.githubusercontent.com/71349228/211192685-fcb78a54-e91a-4621-8a0a-40fccb1630e5.mp4


