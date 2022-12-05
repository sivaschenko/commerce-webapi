The `WishlistItemInterface` contains the following attributes.

Attribute | Data type | Description
--- | --- | ---
`added_at` | String!  | The date and time the item was added to the wish list
`customizable_options`| [SelectedCustomizableOption]! | Custom options selected for the wish list item
`description`| String  | The description of the item
`id`| ID!  | The ID of a `WishlistItemInterface` object
`product` | [ProductInterface](../../graphql/schema/products/interfaces/types/index.md) | Product details of the wish list item
`quantity`| Float!  | The quantity of this wish list item