# Integrations

Click on the integration tile to read its documentation.

## eCommerce platforms

> Packages marked as `Enterprise` are part of Vue Storefrotn Enterprise offering and packages without `From Core Team` badge are created and maintained by our partners.

<IntegrationList>
  <IntegrationTile
    name="Commercetools"
    image="https://www.deloittedigital.de/en/solutions/commercetools/_jcr_content/par/component_container/par/column_ctrl/col3/image.coreimg.png/1593072562788/commercetools-logo.png"
    category="eCommerce"
    isEnterprise="true"
    :from-core="true"
    link="/v2/commercetools"
  />
  <IntegrationTile
    name="Magento"
    image="https://www.plentymarkets.co.uk/tpl/blog/2226/Magento_Logo.png"
    category="eCommerce"
    isBeta="true"
    link="https://docs.vuestorefront.io/magento"
  />
  <IntegrationTile
    name="Salesforce Commerce Cloud"
    image="https://account.demandware.com/dwsso/XUI/themes/salesforce/images/2016sf_CommerceCloud_logo_RGB.png"
    category="eCommerce"
    isBeta="true"
    link="https://docs.vuestorefront.io/sfcc"
  />
  <IntegrationTile
    name="Spryker"
    image="https://getlogovector.com/wp-content/uploads/2019/06/spryker-logo-vector.png"
    category="eCommerce"
    isBeta="true"
    link="https://docs.vuestorefront.io/spryker"
  />
  <IntegrationTile
    name="Shopify"
    image="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Shopify_logo_2018.svg/1024px-Shopify_logo_2018.svg.png"
    category="eCommerce"
    isBeta="true"
    link="/v2/shopify"
  />
  <IntegrationTile
    name="Virto Commerce"
    image="https://tadviser.ru/images/3/3d/Virto_Commerce_logo.png"
    category="eCommerce"
    isWip="true"
  />
  <IntegrationTile
    name="BigCommerce"
    image="https://s3.amazonaws.com/www1.bigcommerce.com/assets/mediakit/downloads/BigCommerce-logo-dark.png"
    category="eCommerce"
    isWip="true"
  />
</IntegrationList>

## Other integrations

<IntegrationList filterable="true">
  <IntegrationTile
    name="Storyblok"
    image="//a.storyblok.com/f/51376/3856x824/fea44d52a9/colored-full.png"
    category="CMS"
    :compatibility="[]"
    isOpenSource="true"
    isEnterprise="true"
    :from-core="true"
    link="https://docs.vuestorefront.io/storyblok"
  />
  <IntegrationTile
    name="Amplience"
    image="https://mma.prnewswire.com/media/1336916/Amplience_Logo.jpg?p=publish"
    isEnterprise="true"
    :compatibility="[]"
    category="CMS"
    :from-core="true"
    link="https://docs.vuestorefront.io/amplience"
  />
  <IntegrationTile
    name="Contentstack"
    image="https://commercetools.com/wp-content/uploads/2019/08/contentstack-full-logo-color-jim-odlum.png"
    isEnterprise="true"
    :compatibility="[]"
    category="CMS"
    :from-core="true"
    link="https://docs.vuestorefront.io/contentstack"
  />
  <IntegrationTile
    name="Contentful"
    image="https://d21buns5ku92am.cloudfront.net/41748/images/347966-contentful-logo-wordmark-dark%20%281%29-4cd185-medium-1582664935.png"
    isEnterprise="true"
    :compatibility="[]"
    category="CMS"
    :from-core="true"
    link="https://docs.vuestorefront.io/contentful/"
  />
  <IntegrationTile
    name="Bazaarvoice"
    image="https://upload.wikimedia.org/wikipedia/en/thumb/6/6a/Bazaarvoice_logo.jpg/220px-Bazaarvoice_logo.jpg"
    :compatibility="[]"
    category="Reviews"
    isEnterprise="true"
    fromCore="true"
    link="./bazaarvoice.html"
  />
  <IntegrationTile
    name="Redis"
    image="https://upload.wikimedia.org/wikipedia/en/thumb/6/6b/Redis_Logo.svg/200px-Redis_Logo.svg.png"
    :compatibility="[]"
    category="Cache"
    isEnterprise="true"
    fromCore="true"
    link="./redis-cache.html"
  />
  <IntegrationTile
    name="LexasCMS"
    image="https://uploads-ssl.webflow.com/5e7cf661c23ac9df156d9c3d/600968c141eb1b7f86436e77_lexascms-logo.svg"
    :compatibility="[]"
    category="CMS"
    link="https://github.com/LexasCMS/vsf-next-lexascms"
  />
  <IntegrationTile
    name="Checkout.com"
    image="https://www.pilcher.london/wp-content/uploads/2020/07/11.-CheckOut.png"
    category="Payment"
    isOpenSource="true"
    :compatibility="['commercetools']"
    :from-core="true"
    link="https://www.npmjs.com/package/@vue-storefront/checkout-com"
  />
  <IntegrationTile
    name="Adyen"
    image="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a2/Adyen_Corporate_Logo.svg/1280px-Adyen_Corporate_Logo.svg.png"
    category="Payment"
    isOpenSource="true"
    isWip="true"
    :from-core="true"
    :compatibility="['commercetools']"
  />
  <IntegrationTile
    name="Bloomreach"
    image="https://commercetools.com/wp-content/uploads/2018/07/bloomreach_logo.png"
    :category="['CMS', 'search']"
    :compatibility="['commercetools']"
    :from-core="true"
    isWip="true"
  />
  <IntegrationTile
    name="Magnolia"
    image="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a1/Magnolia_%28CMS%29_logo.svg/1280px-Magnolia_%28CMS%29_logo.svg.png"
    category="['Authentication']"
    :compatibility="['commercetools']"
    isWip="true"
  />
  <IntegrationTile
    name="Recurly"
    image="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmB9-ZV9SViKzkOzrKlgPvZPC0nbAbLQoAPA&usqp=CAU"
    category="Payment"
    :compatibility="['commercetools']"
    :from-core="true"
    isWip="true"
  />
  <IntegrationTile
    name="Algolia"
    image="https://seekvectorlogo.com/wp-content/uploads/2019/07/algolia-vector-logo.png"
    category="['CMS', 'search']"
    :compatibility="['commercetools']"
    :from-core="true"
    isWip="true"
  />
  <IntegrationTile
    name="Auth0"
    image="https://cdn.geekwire.com/wp-content/uploads/2015/06/Auth0-300x122.png"
    category="['Authentication']"
    :compatibility="['commercetools']"
    :from-core="true"
    isWip="true"
  />
</IntegrationList>