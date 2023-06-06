Hi Kevin!

I'm an ML and Geospatial Engineer at Development Seed, our ML team have been avid users of torchdata and are excited to be getting up to speed with this tool. I'm wondering if you have any interest/time in connecting to hear about how we are using torchdata and provide some guidance on how we could be using it better for our large satellite imagery workloads.

I'm running into consistent pain points when integrating my datapipes with Dataloader V1 or Dataloader V2, which I suspect is because we don't fully understand the ins and outs of setting prefetching, shuffling, buffer sizes, memory pinning, and how these parameters interact with reading services.

I'd love to better understand these points and release examples for the geospatial community on how to take advantage of torchdata for big image streaming workloads. currently we have a couple projects using torchdata we could blog about to highlight how to best construct complex image datapipes and make them simpler:

https://zen3geo.readthedocs.io/en/latest/walkthrough.html managed by my colleague Wei Ji

a WIP to segment oil slick pollution in radar imagery https://github.com/developmentseed/slickformer like [this one](https://github.com/developmentseed/segment-anything-services/blob/main/slick_example.png)

and burned area mapping https://github.com/developmentseed/chabud2023/tree/main

thanks for taking the time to check this request out, it'd be great to meet, chat, and go over one of these projects if you have time! If not, we understand and thank you for your's and Erjia's work on Torchdata!

Best,
Ryan