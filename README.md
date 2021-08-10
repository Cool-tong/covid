cd hedwig

python -m models.bert --dataset LitCovid --model biobert --max-seq-length 512 --batch-size 6 --lr 2e-5 --epochs 30

