# web62
params = url/(params) => vd abc.com/contact, contact là params
query = url/(params)?query => abc.com/contact?page1, page1 là query

interface = giao diện => là điểm cuối endpoints của request tới server => tạo ra URL (uniform resource location ) => có url server biết client muốn gì
=> disadvantages => url không đáp ứng nổi quá nhiều yêu cầu => giải pháp có app chạy trên server để giải quyết, handle và mapping tới các logic 

http protocol ( định dạng dữ liệu) => search HTTP message (gồm 2 phần chính, header và body
)
   http message  PUT : (method) / create_page HTTP (path)
   Content-Type: (định dạng dữ liệu của phần body)


OSI model 


3. Parse: quy trình chuyển đổi từ 1 dữ liệu này thành dữ liệu khác 
- Format: chuyển đổi theo định dạng đặt trước
- Request phải qua middleware tới được clients

//API là interface ( app để mapping url tới dữ liệu và xử lý logic khác nhau qua những entry point) 
    sever side:
        define các entry point

4. REST API: chỉ trả bề dữ liệu chứ không trả về html vì REACT là single page application
5. Validation data và p map với database
=> coi lại callback function 
6. thuộc tính : chứa dữ liệu
phương thức : chứa hàm

7. pathvariable là gì

8. query string
