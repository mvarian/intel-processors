# intel-microprocessors

**Datasets for All Manufactured Intel Microprocessors**

<< insert Intel logo >>

Being enthusiast for data analysis, here's my another dataset project which is about **Intel microprocessors**. Thanks to that, one can realize how the microprocessors have evolved within the last few decades, in terms of many criterions!

This repository begins with the dataset that involves all microprocessors from **Core** series Intel has ever manufactured until **January 2020**. I know this is not limited to just Core processors; thus, in the future, other types of microprocessor families will be added here as individual datasets (such as Pentium, Xeon, Celeron).

_Hopefully, I'm going to perform data analysis over these microprocessors and present them here._

All these info in the dataset is based on Intel ARK [website](https://ark.intel.com/content/www/tr/tr/ark.html).

## Features

The 1st version of the dataset contains these features below:

- `Product`: Name of the manufactured processor
- `Status`: Indicates the availability of the processor
- `Release Date`: Shows when the processor has been released to PC manufacturers or individual users
- `Max. Turbo Freq. (GHz)`: The maximum clock speed the processor can reach while running (in GHz)
- `Base. Freq. (GHz)`: The base clock speed of the processor (in GHz)
- `Cache (MB)`: The total cache capacity of the processor (in MB)
- `Cache Info`: Additional info about the cache
- `Integrated Graphics`: Shows the integrated graphic component used by the processor if exists

**I'm aware that some other necessary features are missing in the dataset!** That's why in the next version, I'm going to include more features in order to make better analysis and get these processors more distinguishable from each other (e.g. # of threads, architecture name, litography, socket type, TDP)...
