Banner Extension for Magneto 2 developed by Risecommerce

Welcome to Banner Slider Extension for Magneto 2 developed by Risecommerce.

The extension lets the store owners place smart banners on their website and also helps in creating unlimited images and video banners for your website to reach the target audience.

##Support: 
version - 2.3.x, 2.4.x

##How to install Extension

1. Download the archive file.
2. Unzip the files
3. Create a folder [Magento_Root]/app/code/Risecommerce/Banner
4. Drop/move the unzipped files to directory '[Magento_Root]/app/code/Risecommerce/Banner'

#Enable Extension:
- php bin/magento module:enable Risecommerce_Banner
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush

#Disable Extension:
- php bin/magento module:disable Risecommerce_Banner
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush
