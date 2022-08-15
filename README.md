# Репозиторий с фильтрацией файлов для PRS
## Main
Файл содержит преобразование из сырых данных в фенотип (.pheno) и в (.cov) файлы для роста и BMI.

Файлы, которые использовались:
* `data/raw_pheno.xlsx` - файл с фенотипами в формате excel 
* `data/merged.fam` - файл из всех образцов. Берется из плинковских файлов 
* `data/merged.rel.id` - файлы с образцами без родственников. Получается командой `--rel-cutoff 0.125` в plink

## Population
Файл для работы с разделением на кластеры (по популяции) образцов.

Файлы, которые использовались:
* `data/population/clust.tsv`, `data/population/clust_some.tsv`, `data/population/clust_eug.csv` - различные разделения на кластера с помощью скрипта на R.