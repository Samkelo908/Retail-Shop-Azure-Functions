🌟 ABCRetailFunctionApp 🌟 ABCRetailFunctionApp is an Azure Function-based web application that integrates with Azure Storage (Tables, Blobs, Queues, and Files) to manage product catalogs and store valuable information efficiently.

🚀 Key Features 🛒 Product Management: Add new products with descriptions, images, prices, and unique IDs. 📂 Azure Table Storage: Store product data in Azure Table Storage for fast retrieval and management. 🖼️ Image Support: Associate products with images using URLs. 🗃️ Azure Files: Upload and manage file shares. 🔄 Queue Processing: Process product orders and manage tasks asynchronously using Azure Queues. 📝 AddProductAsync Function Overview The AddProductAsync function allows you to add new products to Azure Table Storage. This function handles the product's metadata, such as name, description, price, image URL, and unique product ID.

🔧 How It Works HTTP Trigger: This function is triggered via an HTTP POST request. Input: The function expects a JSON payload containing details about the product. Table Storage: Once the product details are received, the function saves them into the Azure Table Storage. Logging: Any errors during the process are logged for easy troubleshooting.

🛠️ Function Explanation HttpTrigger: The function listens for an HTTP POST request. It’s triggered whenever new product data is sent to the endpoint. Azure Table Storage: The product data is saved in Azure Table Storage using a TableEntity, which ensures efficient, scalable storage. Error Handling: The function includes error handling and logging, ensuring that any problems encountered are recorded and responded to appropriately.

Links

Azure links

Cvldv6212st10141464.azurewebsites.net

GitHub Link

https://github.com/VCNMB/vcnmb-cldv6212-2024-part-2-Samkelo908.git

YouTube

Part 1

https://youtu.be/inent5q_Guc

Part 2

https://youtu.be/ZVeE7HvhrJQ
