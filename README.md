В данном репозитории представленны скрипты, использованные для исследования бакалаврской выпускной квалификационной работы и статьи по теме "Продуктивность в зоне степей Евразии и изменения в секвестрации ими углерода"

Репозиторий включает в себя:
- zonal_stata.ipynb - код для фильтрации исходных данных и построения графиков динамики средних величин по экорегионам
- trends_stata.ipynb - код для расчета статистической значимости линейных трендов, построенных ранее в ГИС, по R2
- quantile_regression.ipynb - код для расчета квантильной регрессии NPP/ NEE внутри выбранных экорегионов за 2001-2024 или 2010-2019
- LC.ipynb - код для визуализации матриц переходов между классами землепользования за 2001-2024 или 2010-2019 внутри выбранных экорегионов
- correlation.ipynb - код для расчета корреляции между SPI/температурой с NPP/SR за 2001-2024 или 2010-2019 для выбранных экорегионов
- quantile_npp.ipynb/ quantile_nee.ipynb - коды на ArcPY для квантильных классификаций данных NPP/NEE за каждый год
- NEEbyLULC - для анализа динамики NEE в связи с изменениями в землепользовании/земельном покрове были использованы данные за каждый год 2010-2019; мы определили переходы в землепользовании между каждыми двумя последовательными годами и рассчитали среднее значение и тренд NEE для каждого типа переходов

! Файлов с данными в этом репозитории нет

______
This repository contains scripts used for the bachelor's thesis and article on "Productivity in the Eurasian steppe zone and changes in carbon sequestration".

The repository includes:
- zonal_stata.ipynb - code for filtering the source data and plotting the dynamics of average values by ecoregions
- trends_stata.ipynb - code for calculating the statistical significance of linear trends, obtained earlier in GIS, by R2
- quantile_regression.ipynb - code for calculating the quantile regression of NPP/NEE within selected ecoregions for 2001-2024 or 2010-2019
- LC.ipynb - code for visualizing matrices of transitions between landuse classes for 2001-2024 or 2010-2019 within selected ecoregions
- correlation.ipynb - code for calculating the correlation between SPI/temperature and NPP/SR for 2001-2024 or 2010-2019 for selected ecoregions
- quantile_npp.ipynb/ quantile_nee.ipynb - ArcPy codes for quantile classifications of NPP/NEE data for each year
- NEEbyLULC - the data for each year during 2010-2019 were applied to analyze NEE dynamics, induced by land use/ cover changes; we identified land use/cover transitions between each two consecutive years and accessed NEE mean value and trend for each type on transition

! There are no data files in this repository
