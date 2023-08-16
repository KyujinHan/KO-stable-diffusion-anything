# KO-stable-diffusion-anything
![overview](overview.jpg)  
**Diffusion-based korean text-to-image generation model** 
- 😍Anything: [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/kyujinpy/KO-anything-v4.5)  
- 🤩Disney: [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/kyujinpy/korean-stable-diffusion-disney)
  
# Quick start
```
# Maybe, you will change model_id. Check huggingface!
Korean_stable_diffuion_disney.ipynb # disney style
Korean_stable_diffuion_anything.ipynb # anime style
```
  
# Results
### KO-stable-diffusion-anything (🧨512x512)
<table class="center">
<tr>
  <td style="text-align:center;" colspan="4"><b>Output images</b></td>
</tr>
<tr>
  <td><img src="./anything/image1.png"></td>
  <td><img src="./anything/image2.png"></td>
  <td><img src="./anything/image3.png"></td>              
  <td><img src="./anything/image4.png"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">"걸작, 최고 품질, 1소녀, 흰 머리, 고양이 귀, 눈을 감고, 보는 사람, 귀여운, 스카프, 재킷, 옥외, 거리"</td>
  <td width=25% style="text-align:center;">"풍경, 집, 야외, 하늘, 구름”</td>
  <td width=25% style="text-align:center;">"1소년, 잘생긴, 실내, 앉아있는, 커피 숍, 커피 한 잔"</td>
  <td width=25% style="text-align:center;">"1소년, 강아지 귀, 귀여운, 흰색 스카프, 눈, 관찰자"</td>
</tr>
</table>
  
### KO-stable-diffusion-disney (🧨512x512)
<table class="center">
<tr>
  <td style="text-align:center;" colspan="4"><b>Output images</b></td>
</tr>
<tr>
  <td><img src="./disney/image1.png"></td>
  <td><img src="./disney/image2.png"></td>
  <td><img src="./disney/image3.png"></td>              
  <td><img src="./disney/image4.png"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;">"황금빛 머리카락의 마법 공주, 모던한 디즈니 스타일"</td>
  <td width=25% style="text-align:center;">"아기 사자, 모던한 디즈니 스타일”</td>
  <td width=25% style="text-align:center;">"멋진 뉴욕 풍경, 모던한 디즈니 스타일"</td>
  <td width=25% style="text-align:center;">"아름다운 엘프, 모던한 디즈니 스타일"</td>
</tr>
</table>

# Pre-trained
| Model | huggingface |
| ------------- | ------------- |
| `KO-diffusion-disney` | [huggingface](https://huggingface.co/kyujinpy/KO-stable-diffusion-disney) | 
| `KO-anything-v4.5` | [huggingface](https://huggingface.co/kyujinpy/KO-anything-v4.5) |  
  
# TODO
- [x] Make Colab code
- [x] Share hugging face
- [x] Share KO-stable-diffusion-anything
- [x] Share KO-stable-diffusion-disney

# Acknowledgement
[Bingsu's CLIP](https://huggingface.co/Bingsu/clip-vit-large-patch14-ko)   
[SD-v2](https://github.com/Stability-AI/stablediffusion)   
[anything](https://huggingface.co/xyn-ai/anything-v4.0)  
[MO-DI-diffusion](https://huggingface.co/nitrosocke/mo-di-diffusion)
