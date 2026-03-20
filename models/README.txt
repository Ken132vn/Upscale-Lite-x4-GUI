** IMPORTANT: MODEL SETUP INSTRUCTIONS **

To run this tool, you must manually download the required AI model:

1. VISIT: https://openmodeldb.info/models/4x-NomosWebPhoto-esrgan
2. DOWNLOAD: Select "ONNX .onnx file" (approx. 63.9 MB).
   - Do NOT download .pth or .safetensors files.
3. RENAME: The downloaded file MUST be renamed exactly to:
   4xNomosWebPhoto_esrgan_fp32_opset17.onnx
4. PLACE: Move the renamed file into this "models" folder.

NOTE: 
On the first run, the tool will automatically generate an optimized version 
(FP16) to boost performance on your GPU. Do not delete the generated file.

Model "4x-NomosWebPhoto-esrgan" by Nomos is licensed under CC-BY-4.0.
