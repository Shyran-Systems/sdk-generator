from appwrite.client import Client
from appwrite.services.storage import Storage

client = Client()

(client
  .set_project('')
)

storage = Storage(client)

result = storage.delete_file('[FILE_ID]')