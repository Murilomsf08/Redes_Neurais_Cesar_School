# Projeto Final - Modelos Preditivos Conexionistas

### Murilo da Silva Ferreira

|**Classificação de Imagens**|**YOLOv5**|**PyTorch**|
|--|--|--|

## Performance

O modelo treinado possui performance de **??%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    0/3999     14.2G   0.07625   0.03018   0.02594       181       640: 100% 2/2 [00:04<00:00,  2.29s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:02<00:00,  2.61s/it]
                 all         34         34    0.00574          1     0.0773     0.0317

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    1/3999     14.2G    0.1193   0.02954   0.04164       170       640: 100% 2/2 [00:01<00:00,  1.24it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:01<00:00,  1.40s/it]
                 all         34         34     0.0318       0.87      0.079     0.0396

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    2/3999     14.2G   0.07406   0.02937   0.02558       179       640: 100% 2/2 [00:01<00:00,  1.44it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:01<00:00,  1.16s/it]
                 all         34         34     0.0362      0.818     0.0888     0.0535

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    3/3999     14.2G   0.06972   0.02882   0.02526       182       640: 100% 2/2 [00:01<00:00,  1.39it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.06it/s]
                 all         34         34     0.0374      0.639     0.0869     0.0438

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    4/3999     14.2G   0.06117   0.02785   0.02622       175       640: 100% 2/2 [00:01<00:00,  1.48it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all         34         34    0.00569      0.939       0.07     0.0309

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    5/3999     14.2G    0.0846   0.02745   0.02995       163       640: 100% 2/2 [00:01<00:00,  1.23it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.73it/s]
                 all         34         34    0.00314      0.942     0.0359     0.0105

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    6/3999     14.2G   0.05475   0.02735   0.02611       173       640: 100% 2/2 [00:01<00:00,  1.47it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.67it/s]
                 all         34         34    0.00333          1      0.105     0.0359

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    7/3999     14.2G   0.07805   0.02683   0.02811       164       640: 100% 2/2 [00:01<00:00,  1.45it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.79it/s]
                 all         34         34    0.00334          1      0.176      0.074

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    8/3999     14.2G   0.04787    0.0267   0.02407       175       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:01<00:00,  1.02s/it]
                 all         34         34     0.0351      0.881      0.218      0.134

     Epoch   gpu_mem       box       obj       cls    labels  img_size
    9/3999     14.2G   0.04541   0.02527   0.02306       162       640: 100% 2/2 [00:01<00:00,  1.28it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.72it/s]
                 all         34         34      0.175      0.197      0.265      0.186

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   10/3999     14.2G   0.04373   0.02613   0.02262       178       640: 100% 2/2 [00:01<00:00,  1.41it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.21it/s]
                 all         34         34      0.251      0.219      0.322      0.223

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   11/3999     14.2G   0.04207   0.02554   0.02234       172       640: 100% 2/2 [00:01<00:00,  1.46it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34      0.612      0.316      0.368       0.22

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   12/3999     14.2G   0.06493   0.02349   0.03022       174       640: 100% 2/2 [00:01<00:00,  1.45it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.23it/s]
                 all         34         34      0.582      0.343      0.406      0.263

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   13/3999     14.2G   0.03598   0.02367   0.02063       169       640: 100% 2/2 [00:01<00:00,  1.46it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.26it/s]
                 all         34         34      0.717      0.397      0.434      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   14/3999     14.2G   0.03492   0.02377   0.01962       169       640: 100% 2/2 [00:01<00:00,  1.41it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34      0.665      0.435      0.484      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   15/3999     14.2G   0.03815   0.02166   0.02107       156       640: 100% 2/2 [00:01<00:00,  1.44it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34      0.641      0.581      0.522      0.341

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   16/3999     14.2G    0.0343   0.02243   0.02022       156       640: 100% 2/2 [00:01<00:00,  1.41it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.25it/s]
                 all         34         34       0.64      0.531      0.612      0.404

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   17/3999     14.2G   0.03273   0.02164   0.02078       171       640: 100% 2/2 [00:01<00:00,  1.42it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.34it/s]
                 all         34         34      0.842      0.439      0.683      0.445

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   18/3999     14.2G   0.03305    0.0211   0.01827       163       640: 100% 2/2 [00:01<00:00,  1.46it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.35it/s]
                 all         34         34      0.753      0.528      0.661      0.442

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   19/3999     14.2G   0.03257   0.02206   0.01817       177       640: 100% 2/2 [00:01<00:00,  1.41it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.26it/s]
                 all         34         34      0.608      0.671      0.707      0.442

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   20/3999     14.2G   0.03193   0.02089   0.01704       184       640: 100% 2/2 [00:01<00:00,  1.25it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.33it/s]
                 all         34         34      0.369      0.765      0.679      0.404

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   21/3999     14.2G   0.06277   0.01985   0.03148       181       640: 100% 2/2 [00:01<00:00,  1.40it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34       0.54      0.668      0.744      0.436

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   22/3999     14.2G   0.05202   0.01999   0.02897       170       640: 100% 2/2 [00:01<00:00,  1.39it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.40it/s]
                 all         34         34      0.682      0.556       0.58      0.358

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   23/3999     14.2G   0.03378   0.01825   0.01775       163       640: 100% 2/2 [00:01<00:00,  1.43it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.28it/s]
                 all         34         34      0.701      0.386      0.582      0.376

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   24/3999     14.2G   0.04824    0.0196   0.01907       170       640: 100% 2/2 [00:01<00:00,  1.42it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.59it/s]
                 all         34         34      0.541      0.558      0.637      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   25/3999     14.2G   0.03191   0.02014    0.0155       185       640: 100% 2/2 [00:01<00:00,  1.41it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.36it/s]
                 all         34         34      0.402      0.705      0.617      0.328

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   26/3999     14.2G   0.03099   0.01859   0.01518       171       640: 100% 2/2 [00:01<00:00,  1.38it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.36it/s]
                 all         34         34      0.554      0.776      0.703      0.409

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   27/3999     14.2G   0.02986   0.01799   0.01565       175       640: 100% 2/2 [00:01<00:00,  1.42it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.26it/s]
                 all         34         34      0.692       0.82      0.831      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   28/3999     14.2G   0.03017   0.01775   0.01382       166       640: 100% 2/2 [00:01<00:00,  1.40it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.71it/s]
                 all         34         34      0.651      0.763      0.665      0.364

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   29/3999     14.2G   0.02828   0.01841   0.01326       174       640: 100% 2/2 [00:01<00:00,  1.43it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.52it/s]
                 all         34         34      0.623      0.732      0.717      0.422

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   30/3999     14.2G   0.02991   0.01942    0.0113       186       640: 100% 2/2 [00:01<00:00,  1.43it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.51it/s]
                 all         34         34       0.62       0.71      0.724      0.398

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   31/3999     14.2G     0.048   0.01675   0.02762       163       640: 100% 2/2 [00:01<00:00,  1.41it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.47it/s]
                 all         34         34      0.682      0.685      0.734      0.498

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   32/3999     14.2G   0.03165   0.01822   0.01743       176       640: 100% 2/2 [00:01<00:00,  1.38it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.57it/s]
                 all         34         34       0.66      0.625      0.677      0.374

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   33/3999     14.2G   0.03196   0.01675   0.01182       170       640: 100% 2/2 [00:01<00:00,  1.42it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.25it/s]
                 all         34         34      0.518      0.763      0.646      0.426

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   34/3999     14.2G   0.03373   0.01754   0.01389       179       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.34it/s]
                 all         34         34      0.536      0.677      0.668      0.458

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   35/3999     14.2G   0.03615   0.01829    0.0374       180       640: 100% 2/2 [00:01<00:00,  1.39it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.52it/s]
                 all         34         34      0.317      0.705      0.488      0.276

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   36/3999     14.2G   0.04276   0.01717   0.01127       181       640: 100% 2/2 [00:01<00:00,  1.40it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.19it/s]
                 all         34         34      0.615      0.638      0.613      0.428

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   37/3999     14.2G   0.02713   0.01597    0.0102       172       640: 100% 2/2 [00:01<00:00,  1.40it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.565      0.712      0.701      0.443

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   38/3999     14.2G   0.02906   0.01576   0.01082       165       640: 100% 2/2 [00:01<00:00,  1.40it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.48it/s]
                 all         34         34      0.389      0.651      0.464      0.321

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   39/3999     14.2G   0.05537   0.01621    0.0237       171       640: 100% 2/2 [00:01<00:00,  1.29it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all         34         34      0.408      0.553      0.459      0.264

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   40/3999     14.2G   0.04728   0.01824   0.01469       182       640: 100% 2/2 [00:01<00:00,  1.27it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.37it/s]
                 all         34         34      0.482      0.295      0.209       0.12

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   41/3999     14.2G   0.02535   0.01685  0.009666       177       640: 100% 2/2 [00:01<00:00,  1.40it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.30it/s]
                 all         34         34       0.23      0.407      0.317      0.171

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   42/3999     14.2G    0.0357   0.01579   0.03023       167       640: 100% 2/2 [00:01<00:00,  1.37it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.41it/s]
                 all         34         34      0.191       0.41      0.302      0.207

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   43/3999     14.2G   0.02819     0.016   0.01097       168       640: 100% 2/2 [00:01<00:00,  1.38it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.81it/s]
                 all         34         34      0.651      0.402      0.416      0.159

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   44/3999     14.2G   0.02725    0.0151   0.01123       150       640: 100% 2/2 [00:01<00:00,  1.40it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.45it/s]
                 all         34         34      0.394      0.496      0.469      0.303

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   45/3999     14.2G   0.02668    0.0159   0.01225       163       640: 100% 2/2 [00:01<00:00,  1.38it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.33it/s]
                 all         34         34      0.392      0.583      0.464      0.293

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   46/3999     14.2G    0.0394   0.01659   0.01707       179       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.40it/s]
                 all         34         34      0.331      0.511      0.418      0.201

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   47/3999     14.2G   0.02749   0.01611   0.01232       171       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.47it/s]
                 all         34         34        0.6      0.689      0.618      0.311

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   48/3999     14.2G   0.02688   0.01567  0.009717       172       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.517       0.59      0.592      0.261

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   49/3999     14.2G   0.02939   0.01556  0.009623       180       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.67it/s]
                 all         34         34      0.709      0.687      0.754      0.346

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   50/3999     14.2G   0.03355   0.01602   0.02935       170       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.65it/s]
                 all         34         34      0.651      0.553      0.633      0.242

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   51/3999     14.2G   0.03446   0.01506   0.01141       169       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.60it/s]
                 all         34         34       0.33      0.497       0.41      0.143

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   52/3999     14.2G   0.02737   0.01621  0.008666       177       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.459      0.487       0.51        0.2

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   53/3999     14.2G   0.04599   0.01535   0.03066       174       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34        0.4      0.606       0.46      0.209

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   54/3999     14.2G     0.025   0.01596  0.008151       162       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.46it/s]
                 all         34         34      0.292      0.586      0.352      0.137

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   55/3999     14.2G    0.0236   0.01605   0.01078       164       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.62it/s]
                 all         34         34      0.492      0.273      0.314      0.137

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   56/3999     14.2G   0.02387   0.01546   0.01123       177       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.68it/s]
                 all         34         34       0.84       0.23        0.3      0.153

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   57/3999     14.2G   0.02618   0.01521   0.01969       173       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.60it/s]
                 all         34         34      0.871      0.121      0.145     0.0635

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   58/3999     14.2G   0.02465    0.0153   0.01195       173       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.68it/s]
                 all         34         34          1     0.0887      0.159     0.0856

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   59/3999     14.2G   0.02161   0.01636  0.009812       165       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.96it/s]
                 all         34         34      0.429     0.0303     0.0364     0.0135

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   60/3999     14.2G   0.02397   0.01579  0.007925       163       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.69it/s]
                 all         34         34     0.0122      0.591     0.0391    0.00787

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   61/3999     14.2G   0.02336   0.01551  0.009095       168       640: 100% 2/2 [00:01<00:00,  1.24it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.53it/s]
                 all         34         34     0.0106      0.793     0.0744     0.0235

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   62/3999     14.2G    0.0369   0.01602   0.01691       178       640: 100% 2/2 [00:01<00:00,  1.20it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.90it/s]
                 all         34         34     0.0824      0.121      0.122     0.0459

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   63/3999     14.2G   0.02153   0.01645  0.009657       173       640: 100% 2/2 [00:01<00:00,  1.30it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.191      0.137      0.291      0.147

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   64/3999     14.2G   0.02271   0.01583  0.009833       184       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.40it/s]
                 all         34         34     0.0253          1      0.185     0.0569

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   65/3999     14.2G   0.03865   0.01486   0.02271       167       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.82it/s]
                 all         34         34      0.406     0.0475     0.0551    0.00839

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   66/3999     14.2G    0.0559   0.01512   0.01185       167       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.404     0.0833      0.149     0.0342

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   67/3999     14.2G   0.03432   0.01648   0.03033       192       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.62it/s]
                 all         34         34      0.202      0.195      0.159     0.0441

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   68/3999     14.2G   0.02166   0.01563   0.00872       176       640: 100% 2/2 [00:01<00:00,  1.26it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all         34         34       0.16      0.224      0.207     0.0639

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   69/3999     14.2G   0.03499   0.01577   0.03432       177       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.12it/s]
                 all         34         34      0.125      0.252      0.167     0.0349

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   70/3999     14.2G   0.03009   0.01408   0.01743       165       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.52it/s]
                 all         34         34     0.0905      0.311       0.12     0.0367

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   71/3999     14.2G   0.02162   0.01492   0.00779       176       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.62it/s]
                 all         34         34      0.143      0.338      0.166      0.061

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   72/3999     14.2G   0.05935   0.01575   0.01981       173       640: 100% 2/2 [00:01<00:00,  1.37it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.60it/s]
                 all         34         34       0.28      0.268      0.221     0.0952

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   73/3999     14.2G   0.02385   0.01469  0.009619       171       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.68it/s]
                 all         34         34      0.145      0.283      0.149     0.0859

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   74/3999     14.2G   0.04105   0.01498   0.01622       183       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.80it/s]
                 all         34         34     0.0967      0.341      0.122     0.0488

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   75/3999     14.2G   0.02124   0.01434   0.01059       178       640: 100% 2/2 [00:01<00:00,  1.38it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.36it/s]
                 all         34         34     0.0458      0.515     0.0797     0.0367

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   76/3999     14.2G   0.02786   0.01507   0.02028       183       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.60it/s]
                 all         34         34      0.449      0.636      0.264     0.0681

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   77/3999     14.2G    0.0201   0.01555   0.01022       184       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.52it/s]
                 all         34         34      0.399      0.545      0.121     0.0458

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   78/3999     14.2G   0.02059   0.01492  0.009286       172       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.39it/s]
                 all         34         34     0.0362      0.427     0.0769       0.04

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   79/3999     14.2G   0.02197   0.01444  0.008759       158       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.32it/s]
                 all         34         34      0.048      0.465     0.0933     0.0428

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   80/3999     14.2G   0.02069   0.01522  0.007119       182       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34     0.0837      0.455      0.119     0.0587

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   81/3999     14.2G   0.02611   0.01617   0.01574       180       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.58it/s]
                 all         34         34      0.174      0.609      0.171     0.0835

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   82/3999     14.2G     0.021   0.01578  0.009339       184       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34      0.267      0.639      0.352      0.182

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   83/3999     14.2G   0.02069   0.01359  0.007184       170       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.59it/s]
                 all         34         34       0.36      0.475      0.357      0.198

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   84/3999     14.2G   0.04425   0.01444   0.01463       183       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.57it/s]
                 all         34         34      0.327       0.48      0.402      0.254

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   85/3999     14.2G    0.0203    0.0136  0.006388       178       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.39it/s]
                 all         34         34      0.332       0.47      0.395      0.218

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   86/3999     14.2G   0.02541   0.01576   0.02634       176       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.49it/s]
                 all         34         34      0.363      0.518      0.413      0.299

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   87/3999     14.2G   0.01903   0.01382  0.007997       174       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.31it/s]
                 all         34         34      0.372      0.456      0.438      0.281

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   88/3999     14.2G   0.01868   0.01506  0.007006       180       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.41it/s]
                 all         34         34      0.317      0.526      0.403      0.264

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   89/3999     14.2G   0.02009   0.01463  0.006785       168       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.36it/s]
                 all         34         34      0.791      0.232      0.383      0.212

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   90/3999     14.2G    0.0186   0.01563  0.007611       182       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.12it/s]
                 all         34         34      0.835       0.25      0.507        0.3

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   91/3999     14.2G   0.01809   0.01469  0.008488       174       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.32it/s]
                 all         34         34      0.481      0.562      0.544      0.349

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   92/3999     14.2G   0.01717   0.01462  0.006932       166       640: 100% 2/2 [00:01<00:00,  1.22it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all         34         34      0.739      0.471      0.627      0.387

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   93/3999     14.2G   0.01859   0.01386  0.008172       179       640: 100% 2/2 [00:01<00:00,  1.13it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.661        0.5       0.62      0.427

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   94/3999     14.2G   0.02626   0.01366   0.01582       173       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.39it/s]
                 all         34         34      0.341      0.722      0.605      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   95/3999     14.2G   0.01769   0.01484  0.009399       180       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.58it/s]
                 all         34         34      0.386      0.549      0.544      0.341

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   96/3999     14.2G   0.01763   0.01346  0.007836       164       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.63it/s]
                 all         34         34       0.55      0.612      0.637      0.407

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   97/3999     14.2G   0.03605   0.01474   0.01741       174       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.58it/s]
                 all         34         34      0.718      0.556      0.745      0.502

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   98/3999     14.2G   0.02701   0.01416    0.0138       174       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.45it/s]
                 all         34         34       0.56      0.583       0.72      0.469

     Epoch   gpu_mem       box       obj       cls    labels  img_size
   99/3999     14.2G   0.02337    0.0149   0.01727       174       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.42it/s]
                 all         34         34      0.694      0.548      0.648      0.464

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  100/3999     14.2G   0.03024   0.01524   0.01243       178       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34       0.69      0.534      0.594      0.432

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  101/3999     14.2G   0.02643   0.01459   0.01329       190       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.649      0.702      0.804      0.484

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  102/3999     14.2G    0.0198   0.01417  0.007896       173       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.61it/s]
                 all         34         34       0.72      0.739      0.818      0.563

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  103/3999     14.2G   0.03095   0.01332   0.02996       167       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.55it/s]
                 all         34         34      0.609      0.679      0.768      0.474

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  104/3999     14.2G   0.04986   0.01491    0.0206       187       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.27it/s]
                 all         34         34      0.611      0.768      0.774      0.449

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  105/3999     14.2G   0.01754   0.01508  0.007706       170       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.56it/s]
                 all         34         34      0.887      0.609      0.753      0.508

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  106/3999     14.2G     0.023   0.01527   0.02198       175       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.51it/s]
                 all         34         34      0.814      0.595      0.781      0.478

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  107/3999     14.2G   0.02833   0.01566    0.0125       187       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.31it/s]
                 all         34         34      0.771      0.594      0.691      0.488

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  108/3999     14.2G   0.01901   0.01374  0.008041       173       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.24it/s]
                 all         34         34        0.7      0.672      0.631       0.47

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  109/3999     14.2G    0.0186   0.01581   0.01086       177       640: 100% 2/2 [00:01<00:00,  1.30it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.34it/s]
                 all         34         34      0.579      0.533      0.631      0.474

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  110/3999     14.2G   0.01834   0.01384  0.006951       163       640: 100% 2/2 [00:01<00:00,  1.28it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.32it/s]
                 all         34         34      0.689      0.686      0.746      0.485

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  111/3999     14.2G   0.02215   0.01417  0.008098       182       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.55it/s]
                 all         34         34      0.732      0.596       0.62      0.322

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  112/3999     14.2G   0.02642   0.01488  0.009623       184       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.667      0.525      0.531      0.264

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  113/3999     14.2G   0.03449   0.01368   0.00796       174       640: 100% 2/2 [00:01<00:00,  1.30it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.62it/s]
                 all         34         34      0.725      0.428      0.555      0.338

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  114/3999     14.2G   0.02608    0.0133      0.03       175       640: 100% 2/2 [00:01<00:00,  1.27it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all         34         34      0.574      0.429       0.45      0.263

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  115/3999     14.2G   0.02224   0.01491   0.00914       183       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.27it/s]
                 all         34         34       0.36      0.457      0.336      0.178

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  116/3999     14.2G   0.02535   0.01499   0.02229       176       640: 100% 2/2 [00:01<00:00,  1.37it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.253      0.428      0.304      0.184

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  117/3999     14.2G   0.01753   0.01303  0.007093       171       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.74it/s]
                 all         34         34      0.278      0.487      0.309      0.198

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  118/3999     14.2G   0.02064   0.01525  0.007297       179       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.12it/s]
                 all         34         34      0.206      0.432      0.282      0.184

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  119/3999     14.2G   0.02809   0.01376  0.009088       170       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.79it/s]
                 all         34         34      0.288      0.472      0.323      0.138

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  120/3999     14.2G   0.01753   0.01416  0.005895       178       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.82it/s]
                 all         34         34      0.296      0.215      0.194      0.103

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  121/3999     14.2G   0.01823   0.01285  0.006662       158       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.86it/s]
                 all         34         34      0.176      0.223      0.159      0.102

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  122/3999     14.2G   0.01755   0.01268  0.007162       158       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.71it/s]
                 all         34         34      0.224      0.328      0.208      0.145

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  123/3999     14.2G   0.01984   0.01448  0.008462       184       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.72it/s]
                 all         34         34      0.258      0.354      0.235     0.0987

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  124/3999     14.2G   0.01598   0.01465  0.006124       176       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.83it/s]
                 all         34         34      0.348      0.406      0.306     0.0967

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  125/3999     14.2G   0.01873   0.01321  0.006766       167       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.70it/s]
                 all         34         34      0.305      0.618      0.415      0.126

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  126/3999     14.2G   0.01706   0.01313  0.008133       173       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.63it/s]
                 all         34         34      0.457      0.738      0.602      0.212

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  127/3999     14.2G   0.02763   0.01303   0.00799       172       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.57it/s]
                 all         34         34      0.707      0.781      0.784      0.368

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  128/3999     14.2G   0.02569   0.01354  0.009812       172       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.46it/s]
                 all         34         34      0.669      0.843      0.852      0.478

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  129/3999     14.2G   0.01641   0.01358  0.006645       172       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.892       0.72      0.877      0.518

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  130/3999     14.2G   0.01704   0.01399  0.006257       178       640: 100% 2/2 [00:01<00:00,  1.20it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.61it/s]
                 all         34         34      0.776      0.777      0.844      0.468

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  131/3999     14.2G    0.0226   0.01408  0.009127       180       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.46it/s]
                 all         34         34      0.698      0.826       0.78      0.428

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  132/3999     14.2G   0.01628   0.01352  0.005852       168       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.67it/s]
                 all         34         34      0.739      0.739      0.771      0.431

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  133/3999     14.2G   0.01753   0.01333  0.006358       166       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.65it/s]
                 all         34         34      0.696      0.826      0.821      0.463

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  134/3999     14.2G   0.02807   0.01492   0.01863       191       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.41it/s]
                 all         34         34      0.863       0.77      0.873      0.519

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  135/3999     14.2G   0.01817   0.01314  0.005255       178       640: 100% 2/2 [00:01<00:00,  1.37it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.48it/s]
                 all         34         34      0.893      0.836      0.917      0.511

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  136/3999     14.2G   0.01666   0.01326  0.006309       168       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.823      0.796      0.868        0.5

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  137/3999     14.2G   0.01579   0.01319  0.005702       188       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.37it/s]
                 all         34         34      0.848      0.768       0.86       0.47

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  138/3999     14.2G   0.01588    0.0123  0.004048       167       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.77it/s]
                 all         34         34      0.803       0.82      0.879      0.455

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  139/3999     14.2G   0.01722   0.01286  0.004856       178       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.78it/s]
                 all         34         34      0.806      0.732      0.842      0.387

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  140/3999     14.2G   0.01711   0.01269   0.00625       170       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.41it/s]
                 all         34         34      0.704      0.798      0.809      0.433

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  141/3999     14.2G   0.01673   0.01264  0.004736       171       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.40it/s]
                 all         34         34      0.682      0.851      0.841      0.534

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  142/3999     14.2G   0.01671   0.01276  0.005769       175       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.39it/s]
                 all         34         34      0.743      0.884      0.903      0.536

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  143/3999     14.2G   0.01541   0.01302  0.004354       166       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.68it/s]
                 all         34         34      0.732      0.793      0.849      0.464

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  144/3999     14.2G   0.02498    0.0124   0.02712       167       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.49it/s]
                 all         34         34      0.799      0.841      0.905      0.564

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  145/3999     14.2G   0.01485   0.01151   0.00543       166       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.63it/s]
                 all         34         34      0.724      0.793      0.826      0.554

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  146/3999     14.2G   0.01653   0.01273  0.005457       176       640: 100% 2/2 [00:01<00:00,  1.28it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.47it/s]
                 all         34         34      0.772      0.911      0.892      0.516

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  147/3999     14.2G   0.01696   0.01202  0.003665       162       640: 100% 2/2 [00:01<00:00,  1.27it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.32it/s]
                 all         34         34      0.806      0.795      0.844        0.5

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  148/3999     14.2G   0.02547   0.01384   0.00518       193       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.59it/s]
                 all         34         34      0.912       0.83      0.902      0.523

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  149/3999     14.2G   0.01512   0.01277  0.005391       173       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.61it/s]
                 all         34         34       0.87      0.892      0.918      0.549

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  150/3999     14.2G   0.01499   0.01216  0.004885       175       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.66it/s]
                 all         34         34       0.88      0.897      0.917      0.572

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  151/3999     14.2G    0.0229   0.01182   0.01851       173       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.55it/s]
                 all         34         34      0.937      0.903      0.929      0.551

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  152/3999     14.2G   0.01578   0.01396  0.007713       175       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.30it/s]
                 all         34         34       0.92      0.862      0.905      0.558

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  153/3999     14.2G    0.0155   0.01376  0.005377       168       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.927      0.862      0.897      0.571

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  154/3999     14.2G   0.02221   0.01329  0.008795       169       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.61it/s]
                 all         34         34      0.923      0.848      0.877      0.598

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  155/3999     14.2G   0.01587   0.01221  0.005332       165       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.26it/s]
                 all         34         34      0.924      0.801      0.893      0.593

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  156/3999     14.2G   0.02992   0.01285   0.01555       171       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.46it/s]
                 all         34         34      0.832      0.798      0.874      0.534

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  157/3999     14.2G   0.01659   0.01309  0.007234       173       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34      0.799      0.823      0.842      0.548

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  158/3999     14.2G   0.01736   0.01282  0.006789       178       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.37it/s]
                 all         34         34      0.813      0.771      0.826      0.537

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  159/3999     14.2G    0.0151   0.01273  0.006362       181       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.65it/s]
                 all         34         34      0.771       0.79      0.846      0.591

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  160/3999     14.2G   0.02247    0.0124   0.01378       170       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34      0.878      0.825      0.888      0.541

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  161/3999     14.2G   0.02147   0.01249   0.01112       161       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.52it/s]
                 all         34         34      0.902        0.8      0.885      0.517

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  162/3999     14.2G    0.0139   0.01142  0.004174       174       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.64it/s]
                 all         34         34       0.85      0.735      0.844      0.557

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  163/3999     14.2G   0.01631   0.01273  0.005333       159       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34      0.734      0.752      0.835       0.55

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  164/3999     14.2G   0.01522   0.01326  0.004379       188       640: 100% 2/2 [00:01<00:00,  1.37it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.42it/s]
                 all         34         34      0.687        0.8       0.87      0.502

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  165/3999     14.2G   0.02334   0.01276   0.01176       169       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.37it/s]
                 all         34         34      0.883      0.795      0.901      0.616

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  166/3999     14.2G   0.02266   0.01255   0.01012       175       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.866      0.856      0.917      0.618

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  167/3999     14.2G   0.01595   0.01333  0.005153       194       640: 100% 2/2 [00:01<00:00,  1.24it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all         34         34      0.872      0.835      0.892      0.637

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  168/3999     14.2G   0.01485   0.01364  0.005418       179       640: 100% 2/2 [00:01<00:00,  1.28it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.70it/s]
                 all         34         34      0.851       0.77      0.846      0.517

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  169/3999     14.2G   0.02169   0.01221  0.007772       172       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.37it/s]
                 all         34         34      0.823      0.764      0.828      0.588

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  170/3999     14.2G   0.01594   0.01186  0.005236       176       640: 100% 2/2 [00:01<00:00,  1.37it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.65it/s]
                 all         34         34      0.882      0.738      0.869      0.556

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  171/3999     14.2G   0.01554   0.01296  0.005369       169       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.60it/s]
                 all         34         34        0.9      0.704      0.881      0.642

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  172/3999     14.2G   0.01628   0.01288  0.004607       178       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.49it/s]
                 all         34         34      0.803      0.847      0.871      0.561

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  173/3999     14.2G   0.01572   0.01299   0.00571       175       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.837      0.724      0.825      0.478

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  174/3999     14.2G   0.01733   0.01146  0.003968       151       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.42it/s]
                 all         34         34      0.738      0.692      0.773      0.515

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  175/3999     14.2G   0.01616   0.01139  0.004552       163       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.777      0.718      0.769      0.467

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  176/3999     14.2G   0.01564   0.01235  0.006899       167       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.59it/s]
                 all         34         34      0.813       0.76      0.816       0.55

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  177/3999     14.2G   0.01525   0.01349   0.00618       179       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.60it/s]
                 all         34         34      0.705      0.738      0.761      0.463

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  178/3999     14.2G   0.01508   0.01263  0.004402       168       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.48it/s]
                 all         34         34      0.697      0.755       0.75      0.521

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  179/3999     14.2G   0.01472   0.01279  0.005526       184       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34      0.706      0.684      0.698      0.455

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  180/3999     14.2G   0.01484   0.01258   0.00366       183       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.49it/s]
                 all         34         34      0.578      0.759      0.738      0.463

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  181/3999     14.2G   0.01442   0.01424  0.005756       184       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.70it/s]
                 all         34         34      0.627      0.734       0.77      0.445

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  182/3999     14.2G   0.02726   0.01251   0.00513       182       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34      0.745      0.801      0.855      0.593

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  183/3999     14.2G   0.01604   0.01264  0.004044       179       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.25it/s]
                 all         34         34      0.876      0.709      0.844       0.52

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  184/3999     14.2G   0.01488   0.01293  0.006429       175       640: 100% 2/2 [00:01<00:00,  1.27it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.30it/s]
                 all         34         34      0.777      0.727      0.826      0.537

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  185/3999     14.2G   0.01936   0.01339  0.009021       180       640: 100% 2/2 [00:01<00:00,  1.26it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.01it/s]
                 all         34         34      0.747      0.734      0.784      0.504

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  186/3999     14.2G   0.01462   0.01253  0.006555       169       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.59it/s]
                 all         34         34      0.688      0.814      0.806      0.526

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  187/3999     14.2G   0.01531   0.01229  0.006571       168       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.687      0.765      0.812       0.53

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  188/3999     14.2G   0.01486   0.01227  0.005395       172       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.771      0.795      0.844      0.547

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  189/3999     14.2G   0.01523   0.01315  0.007557       164       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.33it/s]
                 all         34         34      0.733      0.807      0.839        0.5

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  190/3999     14.2G   0.01576   0.01218  0.005116       179       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.64it/s]
                 all         34         34      0.789      0.768      0.842      0.523

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  191/3999     14.2G    0.0323   0.01316     0.019       160       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.53it/s]
                 all         34         34      0.796      0.925      0.864      0.467

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  192/3999     14.2G   0.01601   0.01207  0.004959       175       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.62it/s]
                 all         34         34       0.75      0.886      0.863      0.495

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  193/3999     14.2G   0.01567   0.01225   0.00564       177       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.54it/s]
                 all         34         34      0.647      0.836      0.831      0.439

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  194/3999     14.2G   0.02025   0.01155   0.03821       164       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.59it/s]
                 all         34         34      0.679      0.752      0.831      0.451

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  195/3999     14.2G   0.01699   0.01368  0.005022       169       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.67it/s]
                 all         34         34      0.558      0.695      0.695      0.374

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  196/3999     14.2G   0.01399   0.01261  0.005197       174       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.58it/s]
                 all         34         34      0.513      0.763      0.677      0.352

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  197/3999     14.2G   0.01602   0.01272  0.004317       170       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.79it/s]
                 all         34         34      0.581      0.726      0.711      0.373

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  198/3999     14.2G   0.01546    0.0123  0.006048       176       640: 100% 2/2 [00:01<00:00,  1.23it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.33it/s]
                 all         34         34       0.82      0.814      0.869      0.471

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  199/3999     14.2G   0.01597   0.01231  0.005858       171       640: 100% 2/2 [00:01<00:00,  1.27it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.15it/s]
                 all         34         34      0.812      0.816      0.877      0.581

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  200/3999     14.2G   0.01508   0.01296  0.004041       180       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.757      0.823      0.866      0.563

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  201/3999     14.2G   0.01535   0.01164  0.003797       178       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.59it/s]
                 all         34         34      0.844      0.661      0.873      0.577

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  202/3999     14.2G   0.01504   0.01283  0.004768       181       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34      0.816      0.905      0.931      0.635

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  203/3999     14.2G    0.0142   0.01185  0.004858       170       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.46it/s]
                 all         34         34      0.861      0.914      0.935      0.604

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  204/3999     14.2G   0.01552   0.01303  0.006132       185       640: 100% 2/2 [00:01<00:00,  1.29it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34      0.926      0.841      0.935      0.652

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  205/3999     14.2G   0.02274   0.01189   0.03025       175       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.23it/s]
                 all         34         34      0.901      0.818      0.926      0.608

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  206/3999     14.2G   0.01636   0.01238  0.003755       180       640: 100% 2/2 [00:01<00:00,  1.29it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.37it/s]
                 all         34         34      0.904      0.772      0.907      0.569

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  207/3999     14.2G   0.01596   0.01257  0.005611       169       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.26it/s]
                 all         34         34      0.839      0.827      0.904      0.561

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  208/3999     14.2G   0.02429   0.01306   0.01764       188       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.36it/s]
                 all         34         34      0.895      0.831      0.915      0.594

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  209/3999     14.2G   0.01451   0.01197   0.00542       171       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.57it/s]
                 all         34         34      0.929      0.781      0.899      0.566

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  210/3999     14.2G   0.01439   0.01215  0.004846       168       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.40it/s]
                 all         34         34       0.83      0.886      0.905      0.566

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  211/3999     14.2G   0.01348   0.01274  0.005198       170       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.41it/s]
                 all         34         34      0.867      0.886      0.923      0.605

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  212/3999     14.2G   0.02267   0.01155  0.006314       167       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.63it/s]
                 all         34         34        0.9      0.837      0.862      0.624

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  213/3999     14.2G   0.01447   0.01248  0.005697       183       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.48it/s]
                 all         34         34      0.837      0.884      0.863      0.601

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  214/3999     14.2G   0.01447   0.01162  0.005538       171       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.65it/s]
                 all         34         34       0.84      0.853      0.847      0.611

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  215/3999     14.2G   0.01403   0.01107   0.00491       159       640: 100% 2/2 [00:01<00:00,  1.37it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.36it/s]
                 all         34         34      0.824      0.882      0.848      0.608

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  216/3999     14.2G   0.02777   0.01182   0.01232       189       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.45it/s]
                 all         34         34      0.876      0.823      0.859      0.595

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  217/3999     14.2G   0.01616   0.01151  0.004862       167       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.42it/s]
                 all         34         34      0.836      0.871      0.838      0.611

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  218/3999     14.2G     0.024   0.01288   0.01343       183       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.53it/s]
                 all         34         34      0.849      0.798      0.822      0.504

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  219/3999     14.2G   0.01465   0.01215  0.004844       179       640: 100% 2/2 [00:01<00:00,  1.26it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all         34         34      0.794      0.859      0.835      0.496

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  220/3999     14.2G   0.02136   0.01259  0.005428       179       640: 100% 2/2 [00:01<00:00,  1.26it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.69it/s]
                 all         34         34      0.817       0.84      0.842      0.501

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  221/3999     14.2G   0.01398   0.01182   0.00578       156       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.19it/s]
                 all         34         34      0.871      0.841       0.86      0.636

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  222/3999     14.2G   0.01378   0.01179  0.005014       176       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.63it/s]
                 all         34         34      0.853      0.859       0.88       0.65

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  223/3999     14.2G   0.01435   0.01148  0.005641       168       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.27it/s]
                 all         34         34       0.81      0.859      0.861      0.619

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  224/3999     14.2G   0.01397   0.01219  0.005718       172       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34      0.884      0.707      0.814      0.636

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  225/3999     14.2G   0.01437   0.01186   0.00636       174       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.49it/s]
                 all         34         34      0.876      0.796      0.842      0.652

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  226/3999     14.2G   0.01363   0.01201   0.00324       158       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.74it/s]
                 all         34         34      0.838      0.849      0.853      0.651

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  227/3999     14.2G   0.01564   0.01234  0.006219       182       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.59it/s]
                 all         34         34      0.837      0.852      0.837      0.653

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  228/3999     14.2G   0.01407   0.01088  0.006417       167       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.42it/s]
                 all         34         34      0.767      0.823      0.855      0.678

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  229/3999     14.2G   0.01413    0.0116  0.004613       178       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.61it/s]
                 all         34         34      0.872      0.737      0.857      0.652

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  230/3999     14.2G   0.01946   0.01192   0.02042       170       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.66it/s]
                 all         34         34      0.884      0.811      0.862       0.63

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  231/3999     14.2G   0.01433   0.01183  0.005337       160       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.66it/s]
                 all         34         34      0.876      0.795      0.858      0.675

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  232/3999     14.2G   0.01451   0.01104  0.006829       173       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.51it/s]
                 all         34         34      0.889      0.787      0.845      0.608

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  233/3999     14.2G   0.01443    0.0118  0.004248       172       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.34it/s]
                 all         34         34      0.832      0.748      0.831      0.649

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  234/3999     14.2G   0.01396    0.0117  0.004482       176       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.54it/s]
                 all         34         34      0.808      0.661        0.8      0.616

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  235/3999     14.2G   0.01364   0.01047  0.003855       176       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.776      0.746      0.827      0.593

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  236/3999     14.2G   0.01469   0.01276  0.003991       169       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.55it/s]
                 all         34         34      0.886      0.673       0.85      0.641

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  237/3999     14.2G   0.04085   0.01183   0.00809       175       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.812      0.821      0.826      0.606

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  238/3999     14.2G   0.01382   0.01109  0.004519       167       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.63it/s]
                 all         34         34      0.813      0.848      0.811      0.524

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  239/3999     14.2G    0.0148   0.01187  0.006828       169       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.31it/s]
                 all         34         34      0.869      0.823      0.793      0.543

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  240/3999     14.2G   0.01417   0.01134  0.006122       159       640: 100% 2/2 [00:01<00:00,  1.30it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.31it/s]
                 all         34         34      0.838      0.798      0.796      0.573

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  241/3999     14.2G   0.01383    0.0119  0.004233       188       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.47it/s]
                 all         34         34      0.821      0.828      0.792      0.539

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  242/3999     14.2G   0.01527   0.01138  0.005417       167       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.54it/s]
                 all         34         34      0.797      0.798      0.804      0.525

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  243/3999     14.2G   0.01368   0.01224   0.00506       189       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34      0.774      0.897      0.877      0.562

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  244/3999     14.2G   0.01415   0.01103  0.003403       177       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.53it/s]
                 all         34         34       0.87      0.799      0.853      0.599

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  245/3999     14.2G   0.01343   0.01174  0.005837       176       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.65it/s]
                 all         34         34       0.81      0.859      0.867      0.578

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  246/3999     14.2G   0.02173   0.01202  0.004071       161       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.70it/s]
                 all         34         34      0.802      0.856      0.863      0.616

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  247/3999     14.2G   0.01447   0.01187   0.00388       174       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.55it/s]
                 all         34         34      0.818      0.808      0.841      0.578

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  248/3999     14.2G   0.01435   0.01203  0.004286       181       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.55it/s]
                 all         34         34      0.843      0.802      0.829       0.59

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  249/3999     14.2G   0.01521   0.01137  0.004498       184       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.55it/s]
                 all         34         34      0.813      0.843      0.828       0.52

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  250/3999     14.2G   0.01393   0.01189  0.005231       159       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.32it/s]
                 all         34         34      0.874      0.856      0.864      0.608

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  251/3999     14.2G   0.01339   0.01215  0.003683       182       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.49it/s]
                 all         34         34      0.863      0.851       0.88      0.614

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  252/3999     14.2G   0.01385    0.0108  0.003641       170       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.57it/s]
                 all         34         34      0.856      0.779      0.865      0.647

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  253/3999     14.2G   0.01334   0.01125  0.004076       172       640: 100% 2/2 [00:01<00:00,  1.22it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.49it/s]
                 all         34         34      0.798      0.816      0.886      0.618

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  254/3999     14.2G   0.02395   0.01201  0.005298       182       640: 100% 2/2 [00:01<00:00,  1.22it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.60it/s]
                 all         34         34      0.791      0.834      0.849       0.58

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  255/3999     14.2G   0.02915    0.0116   0.04197       178       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.26it/s]
                 all         34         34      0.758      0.814      0.848      0.584

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  256/3999     14.2G   0.01397   0.01047  0.004335       157       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.45it/s]
                 all         34         34      0.741       0.79      0.846      0.621

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  257/3999     14.2G   0.02709   0.01125   0.00781       177       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.69it/s]
                 all         34         34      0.815      0.822      0.823      0.578

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  258/3999     14.2G   0.01341   0.01167  0.005225       178       640: 100% 2/2 [00:01<00:00,  1.30it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.819      0.818      0.854      0.627

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  259/3999     14.2G   0.02585   0.01101  0.005123       164       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.60it/s]
                 all         34         34       0.86      0.809      0.865       0.68

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  260/3999     14.2G   0.01498    0.0121  0.003766       185       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.869      0.856      0.888       0.64

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  261/3999     14.2G   0.01429   0.01109   0.00323       168       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.45it/s]
                 all         34         34      0.839       0.85      0.884      0.631

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  262/3999     14.2G   0.02498   0.01186  0.006328       177       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.54it/s]
                 all         34         34      0.838      0.907      0.908       0.67

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  263/3999     14.2G   0.01314   0.01095  0.003633       163       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.65it/s]
                 all         34         34      0.811      0.934      0.872      0.658

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  264/3999     14.2G    0.0134   0.01219  0.003892       178       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.40it/s]
                 all         34         34      0.793      0.942      0.861       0.66

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  265/3999     14.2G   0.01413   0.01151  0.004933       168       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34      0.807      0.873      0.852      0.677

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  266/3999     14.2G    0.0144   0.01112   0.00429       181       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.26it/s]
                 all         34         34      0.795      0.863      0.815      0.636

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  267/3999     14.2G   0.03732   0.01148  0.006118       179       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.32it/s]
                 all         34         34      0.736      0.872      0.845      0.606

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  268/3999     14.2G   0.01429    0.0116  0.002729       188       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.48it/s]
                 all         34         34      0.674      0.835      0.858      0.568

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  269/3999     14.2G   0.02432   0.01066   0.01708       177       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.49it/s]
                 all         34         34       0.74      0.867      0.847      0.551

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  270/3999     14.2G    0.0142   0.01127  0.004592       177       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.48it/s]
                 all         34         34      0.839      0.737      0.856      0.566

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  271/3999     14.2G   0.01872   0.01107  0.003139       172       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.47it/s]
                 all         34         34      0.829       0.78      0.848      0.606

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  272/3999     14.2G   0.01397   0.01045  0.005025       168       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.41it/s]
                 all         34         34      0.867      0.746      0.849       0.63

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  273/3999     14.2G    0.0328   0.01099   0.01393       164       640: 100% 2/2 [00:01<00:00,  1.29it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34      0.823      0.867      0.888      0.627

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  274/3999     14.2G    0.0132   0.01107  0.004461       176       640: 100% 2/2 [00:01<00:00,  1.28it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.87it/s]
                 all         34         34       0.91      0.802      0.872      0.637

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  275/3999     14.2G   0.01342   0.01209  0.004757       174       640: 100% 2/2 [00:01<00:00,  1.22it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all         34         34      0.921      0.883      0.908      0.664

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  276/3999     14.2G   0.01464   0.01176  0.005517       175       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.927      0.888      0.906      0.608

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  277/3999     14.2G   0.01424   0.01234  0.003877       173       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.31it/s]
                 all         34         34        0.9      0.907      0.911       0.63

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  278/3999     14.2G   0.01334   0.01157  0.004521       189       640: 100% 2/2 [00:01<00:00,  1.20it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.31it/s]
                 all         34         34       0.91      0.909      0.904      0.556

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  279/3999     14.2G   0.01837   0.01001   0.04804       152       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.54it/s]
                 all         34         34      0.858      0.911      0.909       0.65

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  280/3999     14.2G   0.01538   0.01129  0.007352       177       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.55it/s]
                 all         34         34      0.887      0.886      0.914       0.57

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  281/3999     14.2G   0.01428   0.01019  0.004477       171       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.39it/s]
                 all         34         34      0.872      0.874      0.921      0.604

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  282/3999     14.2G   0.01411   0.01172  0.002993       179       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.63it/s]
                 all         34         34      0.885      0.835      0.904      0.596

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  283/3999     14.2G   0.01464   0.01196  0.003843       174       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.57it/s]
                 all         34         34      0.847      0.856      0.899      0.597

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  284/3999     14.2G   0.01881   0.01059  0.004972       167       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.47it/s]
                 all         34         34      0.921      0.872      0.936       0.61

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  285/3999     14.2G   0.01457   0.01102  0.003783       159       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.67it/s]
                 all         34         34      0.955      0.882       0.91       0.61

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  286/3999     14.2G   0.01286   0.01126  0.004473       174       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.47it/s]
                 all         34         34      0.926      0.856      0.916      0.619

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  287/3999     14.2G    0.0148   0.01085  0.005005       155       640: 100% 2/2 [00:01<00:00,  1.38it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.37it/s]
                 all         34         34      0.918      0.868      0.926      0.658

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  288/3999     14.2G   0.01324   0.01096  0.004407       167       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.848      0.901      0.927      0.616

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  289/3999     14.2G   0.01959   0.01289  0.003612       193       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.35it/s]
                 all         34         34       0.81      0.934      0.918       0.54

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  290/3999     14.2G   0.01622   0.01057  0.006933       168       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.56it/s]
                 all         34         34      0.756      0.912       0.88      0.569

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  291/3999     14.2G   0.01441   0.01127  0.006558       178       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.39it/s]
                 all         34         34      0.833      0.765      0.871      0.572

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  292/3999     14.2G    0.0227   0.01284   0.02388       181       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.40it/s]
                 all         34         34      0.765      0.853      0.875      0.574

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  293/3999     14.2G   0.02689   0.01085   0.02836       167       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.39it/s]
                 all         34         34      0.759      0.772      0.847      0.567

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  294/3999     14.2G    0.0209   0.01116    0.0258       167       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.35it/s]
                 all         34         34      0.741      0.758      0.768      0.442

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  295/3999     14.2G   0.01513   0.01168  0.006305       178       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.33it/s]
                 all         34         34      0.786      0.782      0.782      0.464

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  296/3999     14.2G   0.01359   0.01202  0.005191       175       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.37it/s]
                 all         34         34       0.76      0.712      0.761      0.501

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  297/3999     14.2G   0.01225   0.01106  0.004938       170       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.45it/s]
                 all         34         34      0.717      0.792      0.774      0.489

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  298/3999     14.2G    0.0136   0.01208  0.006264       184       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.775      0.821      0.782      0.503

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  299/3999     14.2G   0.01369   0.01076  0.003804       176       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.53it/s]
                 all         34         34      0.809      0.801      0.827      0.549

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  300/3999     14.2G   0.01836    0.0114  0.008764       167       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34      0.792      0.771       0.78      0.563

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  301/3999     14.2G   0.02443   0.01283   0.01561       179       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.61it/s]
                 all         34         34      0.664      0.644       0.66      0.456

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  302/3999     14.2G   0.01384   0.01101   0.00648       163       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.24it/s]
                 all         34         34      0.679      0.766      0.761       0.56

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  303/3999     14.2G   0.03329   0.01183   0.01518       195       640: 100% 2/2 [00:01<00:00,  1.23it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all         34         34      0.766      0.756      0.756      0.525

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  304/3999     14.2G   0.01636   0.01271  0.005021       183       640: 100% 2/2 [00:01<00:00,  1.27it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.41it/s]
                 all         34         34      0.814       0.62      0.764      0.557

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  305/3999     14.2G   0.01308   0.01187  0.004433       184       640: 100% 2/2 [00:01<00:00,  1.22it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.44it/s]
                 all         34         34      0.645      0.784      0.776      0.506

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  306/3999     14.2G   0.01393    0.0111  0.004938       175       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.64it/s]
                 all         34         34      0.722      0.822      0.821      0.523

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  307/3999     14.2G   0.01823   0.01084  0.009643       164       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.34it/s]
                 all         34         34      0.778      0.809      0.802      0.543

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  308/3999     14.2G     0.021    0.0116    0.0169       179       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.798      0.857      0.842       0.53

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  309/3999     14.2G   0.01295   0.01208  0.005214       197       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.27it/s]
                 all         34         34      0.857      0.862       0.86      0.496

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  310/3999     14.2G   0.02088   0.01206  0.008081       164       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.798      0.895       0.85      0.498

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  311/3999     14.2G   0.01316   0.01033  0.004607       180       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.52it/s]
                 all         34         34      0.805      0.847       0.86      0.489

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  312/3999     14.2G   0.02638   0.01196   0.02415       179       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.47it/s]
                 all         34         34      0.846      0.768      0.841      0.497

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  313/3999     14.2G   0.02773   0.01178   0.03067       182       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.53it/s]
                 all         34         34      0.834      0.757      0.799      0.452

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  314/3999     14.2G   0.01247   0.01042  0.004518       163       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.777       0.81      0.782      0.407

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  315/3999     14.2G   0.01379   0.01119   0.00466       167       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.60it/s]
                 all         34         34       0.77       0.68       0.73      0.392

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  316/3999     14.2G   0.01337   0.01175  0.005352       174       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.63it/s]
                 all         34         34      0.751       0.73      0.735       0.42

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  317/3999     14.2G   0.02177   0.01146   0.01345       168       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.57it/s]
                 all         34         34       0.84      0.797      0.803      0.418

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  318/3999     14.2G   0.01308   0.01186   0.00473       187       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.34it/s]
                 all         34         34      0.797      0.801      0.831      0.426

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  319/3999     14.2G   0.02533   0.01027  0.006238       171       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.40it/s]
                 all         34         34      0.785       0.85      0.858      0.409

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  320/3999     14.2G     0.014    0.0116  0.004638       177       640: 100% 2/2 [00:01<00:00,  1.37it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.89it/s]
                 all         34         34      0.748      0.792      0.844       0.38

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  321/3999     14.2G   0.01472   0.01257   0.00601       187       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.35it/s]
                 all         34         34      0.698      0.782        0.8      0.386

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  322/3999     14.2G   0.01317   0.01035  0.004007       162       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.62it/s]
                 all         34         34      0.888       0.89      0.918      0.523

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  323/3999     14.2G   0.01315   0.01046  0.003455       168       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.58it/s]
                 all         34         34      0.934      0.869      0.917      0.574

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  324/3999     14.2G   0.01312   0.01072  0.005519       165       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.13it/s]
                 all         34         34      0.812      0.886      0.905      0.589

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  325/3999     14.2G   0.01252    0.0106  0.004505       172       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34      0.801      0.836      0.894      0.566

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  326/3999     14.2G   0.01268   0.01167  0.005335       179       640: 100% 2/2 [00:01<00:00,  1.29it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.89it/s]
                 all         34         34       0.74      0.796      0.853      0.553

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  327/3999     14.2G   0.01283   0.01039  0.005387       163       640: 100% 2/2 [00:01<00:00,  1.23it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all         34         34      0.745       0.75      0.822      0.563

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  328/3999     14.2G   0.01377   0.01229  0.004483       177       640: 100% 2/2 [00:01<00:00,  1.30it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.51it/s]
                 all         34         34      0.702       0.73      0.789      0.551

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  329/3999     14.2G   0.03106   0.01081   0.02161       176       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.29it/s]
                 all         34         34       0.58      0.672        0.7      0.493

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  330/3999     14.2G     0.012   0.01125  0.004724       173       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.759      0.599      0.731      0.495

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  331/3999     14.2G   0.01214   0.01079  0.003488       169       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.57it/s]
                 all         34         34      0.701      0.673      0.834      0.544

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  332/3999     14.2G   0.01155   0.01107  0.003854       180       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.46it/s]
                 all         34         34      0.617      0.805      0.862      0.563

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  333/3999     14.2G   0.01829   0.01072  0.009595       164       640: 100% 2/2 [00:01<00:00,  1.37it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.39it/s]
                 all         34         34       0.65      0.643      0.778      0.527

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  334/3999     14.2G   0.01474    0.0115  0.004168       174       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.59it/s]
                 all         34         34      0.666      0.664      0.764      0.532

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  335/3999     14.2G   0.01796   0.01123   0.01531       176       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.38it/s]
                 all         34         34       0.67       0.71      0.823      0.565

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  336/3999     14.2G   0.01279    0.0126  0.005733       175       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.57it/s]
                 all         34         34      0.748       0.73      0.832      0.635

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  337/3999     14.2G   0.01256   0.01135   0.00408       165       640: 100% 2/2 [00:01<00:00,  1.30it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.44it/s]
                 all         34         34      0.804      0.787      0.871      0.639

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  338/3999     14.2G   0.01407   0.01177  0.002881       178       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.56it/s]
                 all         34         34      0.765      0.918      0.908      0.649

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  339/3999     14.2G   0.01346    0.0115   0.00367       178       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.33it/s]
                 all         34         34      0.799      0.818      0.865      0.586

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  340/3999     14.2G   0.01242   0.01163  0.003819       182       640: 100% 2/2 [00:01<00:00,  1.31it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.37it/s]
                 all         34         34      0.771      0.828      0.855      0.583

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  341/3999     14.2G   0.02359   0.01107  0.006189       173       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.74it/s]
                 all         34         34      0.771      0.815      0.841      0.556

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  342/3999     14.2G   0.01847   0.01088   0.01448       183       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.63it/s]
                 all         34         34      0.738        0.8      0.835      0.568

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  343/3999     14.2G   0.02567   0.01119   0.01235       178       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.60it/s]
                 all         34         34       0.72      0.739      0.791      0.541

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  344/3999     14.2G   0.01293   0.01135  0.006842       178       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.64it/s]
                 all         34         34      0.853      0.746      0.827      0.531

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  345/3999     14.2G   0.01352   0.01141  0.005233       174       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.838      0.837       0.85      0.524

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  346/3999     14.2G   0.01286   0.01172  0.005664       162       640: 100% 2/2 [00:01<00:00,  1.33it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.43it/s]
                 all         34         34      0.885      0.842      0.861      0.567

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  347/3999     14.2G   0.01273   0.01128  0.003721       160       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.74it/s]
                 all         34         34        0.9      0.851      0.901      0.585

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  348/3999     14.2G   0.01363   0.01127  0.003114       172       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.42it/s]
                 all         34         34      0.904      0.872      0.918      0.603

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  349/3999     14.2G   0.01613   0.01149    0.0104       184       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.56it/s]
                 all         34         34      0.932       0.87      0.913      0.546

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  350/3999     14.2G   0.01307    0.0119  0.003527       168       640: 100% 2/2 [00:01<00:00,  1.34it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.50it/s]
                 all         34         34      0.894      0.874      0.903      0.549

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  351/3999     14.2G   0.01355   0.01055  0.003904       173       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.41it/s]
                 all         34         34      0.875      0.874      0.891      0.516

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  352/3999     14.2G   0.01347   0.01156  0.003754       168       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.42it/s]
                 all         34         34      0.896      0.851      0.889      0.583

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  353/3999     14.2G   0.01221   0.01006  0.003457       168       640: 100% 2/2 [00:01<00:00,  1.36it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.65it/s]
                 all         34         34      0.836      0.842      0.887      0.522

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  354/3999     14.2G    0.0129   0.01072  0.002629       159       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.55it/s]
                 all         34         34      0.898      0.784      0.883      0.614

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  355/3999     14.2G   0.03507   0.01135  0.009347       186       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.32it/s]
                 all         34         34       0.93      0.825      0.905      0.632

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  356/3999     14.2G   0.02541   0.01144   0.01581       172       640: 100% 2/2 [00:01<00:00,  1.35it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.17it/s]
                 all         34         34      0.885      0.843      0.899      0.615

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  357/3999     14.2G   0.01195   0.01132  0.001864       157       640: 100% 2/2 [00:01<00:00,  1.32it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.52it/s]
                 all         34         34      0.875      0.792      0.858      0.544

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  358/3999     14.2G   0.01305   0.01092  0.003547       171       640: 100% 2/2 [00:01<00:00,  1.24it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.65it/s]
                 all         34         34       0.83      0.733      0.817      0.528

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  359/3999     14.2G    0.0176   0.01028  0.009019       157       640: 100% 2/2 [00:01<00:00,  1.19it/s]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.31it/s]
                 all         34         34       0.72      0.759      0.777      0.473
Stopping training early as no improvement observed in last 100 epochs. Best results observed at epoch 259, best model saved as best.pt.
To update EarlyStopping(patience=100) pass a new patience value, i.e. `python train.py --patience 300` or use `--patience 0` to disable EarlyStopping.

360 epochs completed in 0.247 hours.
Optimizer stripped from runs/train/exp/weights/last.pt, 14.5MB
Optimizer stripped from runs/train/exp/weights/best.pt, 14.5MB

Validating runs/train/exp/weights/best.pt...
Fusing layers... 
Model summary: 213 layers, 7018216 parameters, 0 gradients, 15.8 GFLOPs
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  2.37it/s]
                 all         34         34       0.86      0.808      0.865       0.68
           Bicicleta         34         12      0.964      0.667      0.845      0.652
                Moto         34         11      0.724          1      0.905       0.74
            Patinete         34         11      0.893      0.758      0.844      0.648


### Evidências do treinamento

https://wandb.ai/cesarshool/YOLOv5?workspace=user-murilomsf

## Roboflow

https://app.roboflow.com/moto-gj5fy/moto-nik1g/2 

## HuggingFace

