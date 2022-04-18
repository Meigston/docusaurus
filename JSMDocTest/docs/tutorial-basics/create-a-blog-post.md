# Endpoints do Marketplace Juntos Somos Mais

## Token para testes


<token-component/>
## Gerenciamento cadastro de Produtos

<Swagger
      url = "https://hml-api-loja.juntossomosmais.com.br/catalog/documentation/swagger.json"
      urlBase = "https://hml-api-loja.juntossomosmais.com.br/catalog/"
      noModel
      noTitle
  >

   <Api operationId="GetListLot"/>
   <Api operationId="GetLot"/>
   <Api operationId="PostAddLot"/>
   <Api operationId="PutUpdateLot"/>
   <Api operationId="DeleteLot"/>


   <Api operationId="GetProductsCatalog"/>
   <Api operationId="GetMaterialCodeCatalog"/>
   <Api operationId="PostAddProductCatalogV2"/>
   <Api operationId="PutUpdateProductCatalogV2"/>


   <Api operationId="GetNormalizedCategoryTree"/>


   <Api operationId="GetPrices"/>
   <Api operationId="AddProductPrice"/>


   <Api operationId="GetProducers"/>
</Swagger>

## Gerenciamento cadastro de clientes
<tip-component message="Para novas integrações utilize as rotas V2"></tip-component>
<Swagger
      url = "https://hml-api-loja.juntossomosmais.com.br/customer/documentation/swagger.json"
      urlBase = "https://hml-api-loja.juntossomosmais.com.br/customer/"
      noModel
      noTitle
  >

   <Api operationId="GetListCustomer"/>
   <Api operationId="PostAddCustomerAsync"/>
   <Api operationId="PutUpdateCustomerAsync"/>
</Swagger>

## Gerenciamento informações Financeiras

<Swagger
      url = "https://hml-api-loja.juntossomosmais.com.br/financial/documentation/swagger.json"
      urlBase = "https://hml-api-loja.juntossomosmais.com.br/financial/"
      noModel
      noTitle
  >

   <Api operationId="GetListCreditLimit"/>
   <Api operationId="PutListCreditLimit"/>


   <Api operationId="GetListInvoice"/>
   <Api operationId="PutListInvoice"/>
   <Api operationId="PostListInvoice"/>
</Swagger>

## Gerenciamento de Acessos

<Swagger
      url = "https://hml-api-loja.juntossomosmais.com.br/identity/documentation/swagger.json"
      urlBase = "https://hml-api-loja.juntossomosmais.com.br/identity/"
      noModel
      noTitle
  >

   <Api operationId="PostToken"/>
</Swagger>

## Gerenciamento Cadastro Seller

<Swagger
      url = "https://hml-api-loja.juntossomosmais.com.br/seller/documentation/swagger.json"
      urlBase = "https://hml-api-loja.juntossomosmais.com.br/seller/"
      noModel
      noTitle
  >

   <Api operationId="GetListSellerParameter"/>
   <Api operationId="GetByParameterId"/>
   <Api operationId="PostAddSellerParameter"/>
   <Api operationId="PutUpdateSellerParameter"/>
   <Api operationId="DeleteSellerParameter"/>
</Swagger>

## Gerenciamento de Pedidos e Variação de preço

<Swagger
      url = "https://hml-api-loja.juntossomosmais.com.br/sale/documentation/swagger.json"
      urlBase = "https://hml-api-loja.juntossomosmais.com.br/sale/"
      noModel
      noTitle
  >

   <Api operationId="GetDailyOrders"/>
   <Api operationId="UpdateOrder"/>


   <Api operationId="GetOnePriceVariation"/>
   <Api operationId="GetManyPriceVariations"/>
   <Api operationId="AddPriceVariation"/>
   <Api operationId="AlterPriceVariation"/>
   <Api operationId="DeleteOnePriceVariation"/>
</Swagger>

## Gerenciamento de Estoque e Frete

<Swagger
      url = "https://hml-api-loja.juntossomosmais.com.br/sphinx/documentation/swagger.json"
      urlBase = "https://hml-api-loja.juntossomosmais.com.br/sphinx/"
      noModel
      noTitle
  >

   <Api operationId="GetStocks"/>
   <Api operationId="PostStock"/>
   <Api operationId="UpdateStock"/>
   <Api operationId="DeleteStock"/>


   <Api operationId="GetFreight"/>
   <Api operationId="PostFreight"/>
   <Api operationId="UpdateFreight"/>
   <Api operationId="DeleteFreight"/>
</Swagger>

