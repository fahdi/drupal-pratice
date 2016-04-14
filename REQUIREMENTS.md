You are required to build a Product Catalogue Management System in Drupal 7+ (Preferrably the latest version), which allows to add/edit/delete products with the following product information.

**Basic Product:**

| Name        |Type                         |  Purpose |
|-------------|:----------------------------|:---------|
| ID          |  Auto Number                | To reference from other parts of the Project |
| Title       |  Text                       | This will store title of the product |
| Description |  Text                       | This will store product description |
| SKU         |  Text                       | This will store product Sku information |
| Images      | Multiple Image Files        | This will store all the product images |
| Price       | Number                      | To store price |
| Status      | Enum (“Active”, “Inactive”) | to show the product status |


**Product Variants:**

Every product can have Color or Size variants. A color variant will have the following information:

**Color Variant:**

| Name              |Type                                           |  Purpose |
|-------------      |:----------------------------                  |:---------|
| ID                | Auto Number                                   | For Reference|
| Color Variant ID  | Text                                          | |
| Images            | Multiple Images specific to a color variant   | |
| Price             | Number                                        | Color variant specific price |

**Size Variant:**

| Name              |Type         |  Purpose |
|-------------      |:------------|:---------|
| ID                | Auto Number | For Reference|
| Size              | Text        | |
| Price             | Number      | Size variant specific price |

**Product Types or Category specific information:**

Different type of products will have different information attach to those. Assume a Mobile Phone will have different fields of information (e.g. Sim Slot, Internal Memory, Camera in Mega Pixel etc) vs a Laptop which will have different fields (e.g. Hard Drive, Memory etc) . Similarly, a T-shirt will have different information (e.g. Size (S,M,L), Material like Cotton etc). 

**Note: You need to store all of this information efficiently in the System keeping in mind we will have hundreds of different product types in the Future.**

**Deliverables:**

1. Module/s added to the System (Custom + Contrib), Other changes made to Core if any
2. Document explaining all the steps involved to set it up.


