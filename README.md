beat
====
class PublishResource < ActiveResource::Base
  self.site = ENDPOINT
  self.user = USERNAME
  self.password = APITOKEN
  # self.proxy = "http://127.0.0.1:8888"
  self.timeout = 30
  self.include_format_in_path = false
  self.element_name = "publish"
  self.collection_name = "publish"
end
