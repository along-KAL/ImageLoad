# ImageLoad
实现了批量下载图片，防止错位，采样压缩， 内存缓存，磁盘缓存等功能，主要对线程池，图片采样压缩，LruCache，DiskCache的学习与使用



使用方法：

sampleImageLoad = new SampleImageLoad(Context context);

  sampleImageLoad.initParams()
                .setUrl(path)
                .setImageSize(-1,-1)
                .setImageView(imageView)
                .attachToView();
