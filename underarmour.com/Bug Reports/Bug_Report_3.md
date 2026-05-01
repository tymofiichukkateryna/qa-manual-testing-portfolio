|                     |                                                                                                                                            |
|---------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Summary:            | Missing quantity selector on a product detail page and restrictive limit of 10 items in the Bag.                                           |
| Priority:           | High                                                                                                                                       |
| Environment         | Production                                                                                                                                 |
| Device:             | Smartphone                                                                                                                                 |
| OS:                 | Android 16                                                                                                                                 |
| App version:        | 2.73                                                                                                                                       |
| Network:            | Wi-Fi                                                                                                                                      |
|                     |                                                                                                                                            |
| Steps to Reproduce: |                                                                                                                                            |
| 1.                  | Open the Under Armour app.                                                                                                                 |
| 2.                  | Select any product without  "only a few left" quantity                                                                                     |
| 3.                  | Observe the page for a Quantity selector (dropdown or +/- button).                                                                         |
| 4.                  | Tap "Add to Bag" and go to the Bag                                                                                                         |
| 5.                  | Try to change the quantity of the added item to more than 10.                                                                              |
| 6.                  | Try to add the 11th item by returning to the product detail page and tapping "Add to Bag" again.                                           |
| Expected Result:    |                                                                                                                                            |
| ·                   | Step 3: User should be able to select the desired quantity directly on the product page.                                                   |
| ·                   | Step 5: User should be able to select a quantity higher than 10 in the Bag.                                                                |
| Actual Result:      |                                                                                                                                            |
| ·                   | No quantity selector exists on the product page; items can only be added one by one tapping each time “add to bag”.                        |
| ·                   | The Bag limits the quantity to a maximum of 10 items in the dropdown list.                                                                 |
| ·                   | Adding an 11th and more item requires a manual, repetitive process of returning by returning to the product page and tapping "Add to bag". |
| Repro rate:         |                                                                                                                                            |
| ·                   | 100%                                                                                                                                       |
| Notes:              |                                                                                                                                            |
| ·                   | The issue persists for both logged-in users and in Guest mode.                                                                             |
| ·                   | This creates a poor user experience for bulk purchases.                                                                                    |
| Attachments:        |                                                                                                                                            |
| ·                   | video_bug_reproduction.mp4                                                                                                                 |
| ·                   | https://drive.google.com/file/d/1Abutw6g6MxCsgxIzbSX2cyfLH83LX73N/view?usp=sharing                                                         |
