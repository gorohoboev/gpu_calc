Функция написана в файле: 
  medianFilterGPU.h

Результат:
  result.jpg

Для сборки (Intel oneAPI / DPC++):
  icpx -O3 -fsycl -mavx2 main.cpp -o median_filter

Запуск:
  ./median_filter
