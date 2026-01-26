# Use Case Relationships

Use case relationships are used to show how different use cases are connected to each other.

- The Generate Ticket use case «includes» the Create QR Code use case, because a QR code must be created whenever a ticket is generated.

- The Validate Ticket use case «includes» the Check Database use case, as ticket details must be verified from the database.

- The Scan Ticket use case «extends» the Validate Ticket use case when the QR code is successfully scanned.

- The Login User use case «includes» the Authenticate User use case for security purposes.
