# NHÓM 2 - CHUỖI KHỐI

Thành viên:
1. Hoàng Thị Tuyết
2. Vũ Hoàng Linh
3. Phạm Văn Lượng
4. Lê Thị Thu Trang


# **1. Chuỗi khối là gì?**

[Chuỗi khối](https://vi.wikipedia.org/wiki/Blockchain#cite_note-fortune20160515-2 ) (blockchain) [1] là một cơ sở dữ liệu phân cấp lưu trữ thông tin trong các khối thông tin được liên kết với nhau và mở rộng theo thời gian. Mỗi khối thông tin đều chứa thông tin về thời gian khởi tạo và được liên kết tới khối trước đó, vì vậy cơ sở dữ liệu này được gọi là chuỗi khối. Chuỗi khối được thiết kế để chống lại việc thay đổi của dữ liệu: Một khi dữ liệu đã được ghi thì sẽ không có cách nào thay đổi được nó.

**Sự phát triển của chuỗi khối ( cách mạng ) có thể chia làm 3 giai đoạn hay 3 hướng:**

-  Chuỗi khối 1.0 là tiền tệ, việc triển khai cryptocurrencies ( đông tiền mã hóa) trong các ứng dụng liên quan đến tiền mặt, chẳng hạn như chuyển tiền, gửi tiền và các hệ thống thanh toán số.
- Chuỗi khối 2.0 hợp đồng thông minh, chuỗi khối được sử dụng rộng hơn, không chỉ giới hạn ở các giao dịch tiền mặt mà trên toàn bộ các ứng dụng kinh tế, thị trường như chứng khoán, trái phiếu, giao dịch tương lai, thế chấp, cho vay, tài sản thông minh và hợp đồng thông minh.
- Chuỗi khối 3.0 là ứng dụng chuỗi khối vượt ra ngoài lĩnh vực tiền tệ, tài chính và thị trường- đặc biệt trong các lĩnh vực của chính phủ, y tế, khoa học, văn hoá, và nghệ thuật.

# **2. Bitcoin và chuỗi khối khác nhau như thế nào?**

[Bitcoin](https://vi.wikipedia.org/wiki/Bitcoin) [2] là một dạng tiền tệ ảo được tạo ra lần đầu bởi Satoshi Nakamoto vào năm 2008. Cũng được biết đến với cái tên "tiền tệ mã hoá", nó được tạo ra với mục đích bỏ quá sự kiểm soát tiền tệ của chính phủ và để đơn giản hoá giao dịch trên mạng bằng cách bỏ qua các bước của giao dịch trung gian với bên thứ ba. Tất nhiên, để đạt được điều này cần nhiều thứ hơn là chỉ có tiền. Phải có một cách bảo mật để tạo ra giao dịch với tiền tệ ảo.

Giao dịch bitcoin được lữu trữ và chuyển giao sử dụng một "sổ cái" phân tán trên một mạng lưới peer-to-peer mở, công khai và ẩn danh. Chuỗi khối chính là công nghệ được sử dụng để tạo ra cuốn sổ cái của giao dịch Bitcoin.

# **3. Bitcoin chuỗi khối hoạt động như thế nào?**

Bitcoin chuỗi khối dạng đơn giản nhất là một cơ sở dữ liệu hay một "sổ cái" chứa đựng những bản ghi về các giao dịch Bitcoin. Tuy nhiên, bởi vì cơ sở dữ liệu này phân tán trên mạng lưới peer-to-peer và không có một ai là trung tâm, nên những ai tham gia đều phải chấp nhận sự đúng đắn của một giao dịch trước khi nó được ghi lại. Sự đồng thuận này, được biết với cái tên là "consensus" (nhất trí), và nó được tạo ra thông qua một quy trình gọi là "mining" (đào mỏ).

Sau khi ai đó sử dụng Bitcoins, cái thợ đào mỏ tham gia vào một quá trình tính toán phức tạp, tiêu tốn tài nguyên máy tính để xác minh tính chính xác của giao dịch. Thông qua việc đào mỏ, một "proof of work" (bằng chứng công việc) phù hợp với những yêu cầu cho trước, được tạo ra. "Bằng chứng công việc" là một đoạn dữ liệu phải mất nhiều thời gian và tiền bạc để tạo ra, nhưng lại có thể dễ dàng được người khác xác minh. Để được coi là một giao dịch chính xác trong chuỗi khối, một bản ghi đơn lẻ phải có một "bằng chứng công việc" để cho thấy đã đạt được consensus. Bằng thiết kế này, các bản ghi giao dịch không thể bị xáo trộn hay thay đổi sau khi chúng được thêm vào chuỗi khối.

![Kết quả hình ảnh cho hoạt động chuỗi khối](http://hocvientienao.com/wp-content/uploads/2017/04/infographics001-01-1-1.png)


## **3.1. Giao dịch**

Với kỹ thuật này, 1 đồng tiền ảo – tiền số được định nghĩa là 1 chuỗi các chữ ký số. Mỗi người khi chuyển đồng tiền của mình cho người nhận bằng cách ký lên hàm băm của giao dịch trước đó và khóa công khai của người nhận, rồi thêm chữ ký số đó vào cuối đồng tiền. Người nhận có thể xác thực chữ ký để chứng minh quyền sở hữu của mình với đồng tiền ảo này.

![Quá trình giao dịch](https://d2mxuefqeaa7sj.cloudfront.net/s_BC5C8AA54AA86AEBF7D7D4BDCD271C051B03A344DD960F842E0176C2079EAE55_1512380020124_file.png)


Vấn đề ở đây là người thụ hưởng không thể xác minh rằng một trong những chủ sở hữu trước đó đã không chi tiêu gấp đôi. Một giải pháp phổ biến là sử dụng một đơn vị trung tâm đáng tin cậy ( mint – sở đúc tiền) để kiểm tra tất cả các giao dịch. Sau mỗi lần giao dịch, đồng tiền ảo được thu hồi và phát hành với chủ sở hữu mới. Chỉ những đồng tiền phát hành từ Mint mới được xác định là đáng tin cậy và không bị chi tiêu gấp đôi. Với giải pháp này, tất cả các giao dịch đều phụ thuộc vào sự tồn tại của Mint. Do vậy cần 1 giải pháp độc lập hơn để biết rằng trước đó người chuyển tiền không kí 1 giao dịch nào khác. Với tiêu chí, giao dịch xảy ra sớm nhất/ đầu tiên là giao dịch hợp lệ, các giao dịch sau đó không cần quan tâm. Để thực thi được giao dịch như vậy mà không cần bên thứ 3, cần :


- Các giao dịch phải được thông báo công khai


- Một hệ thống mà các thành viên đều đồng thuận về 1 lịch sử giao dịch mà họ nhân được ( sự đồng thuận )

Người thụ hưởng cần đảm bảo rằng tại thời điểm giao dịch phần lớn các nút mạng đồng ý rằng đó là giao dịch đầu tiên mà nó nhận được.


## **3.2. Máy chủ dấu thời gian (Timestamp Server)**

Giải pháp bắt đầu với 1 máy chủ dấu thời gian. Máy chủ này hoạt động bằng cách sử dụng hàm băm, hash 1 chuỗi các item theo thời gian và công khai rộng rãi kết quả. Mỗi khối bao gồm các giao dịch trong 1 khung thời gian và hask của khối trước đó.

![](https://d2mxuefqeaa7sj.cloudfront.net/s_BC5C8AA54AA86AEBF7D7D4BDCD271C051B03A344DD960F842E0176C2079EAE55_1512380020000_file.png)




## **3.3. Bằng chứng về việc làm (Proof-of-Work)**

Proof of work (PoW) là một mẩu dữ liệu mà việc sản xuất ra nó đủ khó ( về mặt giá cả, thời gian thực hiện ) nhưng lại dễ dàng để cho người khác xác nhận đảm bảo thỏa mãn 1 số nhu cầu nhất định. Việc sản xuất ra 1 PoW có thể là 1 quá trình lặp đi lặp lại, ngẫu nhiên với xác suất rất thấp đến mức cần rất nhiêu lần thử nghiệm và lỗi cho đến khi 1 PoW hợp lệ được tạo ra. “ – Nguổn: [https://en.bitcoin.it/wiki/Proof_of_work](https://en.bitcoin.it/wiki/Proof_of_work)


![](https://d2mxuefqeaa7sj.cloudfront.net/s_BC5C8AA54AA86AEBF7D7D4BDCD271C051B03A344DD960F842E0176C2079EAE55_1512380020243_file.png)


Bitcoin sử dụng hệ thống PoW tương tự với Hashcash. PoW thực hiện quét các giá trị mà khi hash ( theo SHA 256 chẳng hạn ), giá trị trả về bắt đầu bằng 1 số các bit 0. Ở đây, giá trị Target value = số bit 0, dữ liệu có thể verify bằng cách thực hiện hàm băm. Đối với mạng timestamp, chúng ta thực hiện bằng cách giá trị NONCE cho đến khi đạt được số bit 0 cần thiết và tạo ra khối hợp lệ. Khi CPU đã tạo được 1 khối hợp lệ, nếu muốn tạo 1 khối khác thì phải lặp lại từ đầu quá trình này. Khi khối đã được nối vào chuỗi, nếu muốn thay đổi giá trị của khối thì phải khởi tạo lại cả các khối phía sau nó.


![](https://d2mxuefqeaa7sj.cloudfront.net/s_BC5C8AA54AA86AEBF7D7D4BDCD271C051B03A344DD960F842E0176C2079EAE55_1512380020010_file.png)


Cơ chế của PoW cũng giải quyết được bài toán ra quyết định dựa trên đa số. Nếu đa số được tính trên địa chỉ IP, nó có thể bị thao túng bởi bất cứ ai chiếm quyền phân bố địa chỉ IP. PoW hoạt động dựa trên cơ chế 1 CPU = 1 phiếu bầu. Quyết định đa số sẽ đại diện bởi chuỗi dài nhất. Nếu đa số các CPU điều khiển bởi các node trung thực, chuỗi trung thực sẽ phát triển nhanh nhất và vượt xa các chuỗi cạnh tranh. Để thay đổi giá trị 1 khối thứ N trong chuỗi, kẻ tấn công sẽ phải thực hiện lại công việc PoW khối thứ N và các khối sau đó, đến khối hiện tại với tốc độ vượt qua các nút trung thực.

## **3.4 Mạng**

Mạng chuỗi khối hoạt động theo các bước:


- Giao dịch mới được truyền (broadcast) đến toàn mạng


- Mỗi node sẽ gộp các giao dịch mới vào khối


- Mỗi node sẽ thực hiện tìm kiếm PoW cho khối của nó


- Khi 1 node tìm được PoW nó sẽ truyền khối đó cho toàn bộ các node.


- Các node chỉ chấp nhận khối khi tất cả các giao dịch trong đó là hợp lệ và chưa chi tiêu

- Các node thể hiện sự chấp nhận khối bằng cách dùng giá trị băm của khối đó khi tạo khối tiếp theo.

Các node luôn luôn coi chuỗi dài nhất là chuỗi đúng và luôn mở rộng dựa trên chuỗi đó. Nếu 2 node broadcast 2 phiên bản khác nhau của khốitiếp theo, 1 số node sẽ nhận được 2 khối này theo thứ tự khác nhau. Trong trường hợp này, nó sẽ tiếp tục làm việc & mở rộng trên khối đầu tiên mà nó nhận được, khối còn lại sẽ lưu lại để phân nhánh sau này. Khi node nhận được khối PoW tiếp theo, nó sẽ ghép vào chuỗi và loại bỏ nhánh ngắn hơn, tiếp tục làm việc dựa trên chuỗi dài hơn.

Việc broadcast giao dịch mới cũng không nhất thiết phải broadcast đến toàn bộ các node. Mỗi khi giao dịch mới đến node, nó sẽ được gộp vào khối. Việc gửi các khối broadcast cũng phải xử lý được việc mất khối. Nếu 1 node không nhận được khối, khi nhận được khối tiếp theo và nhận ra mình mất khối nào, nó sẽ yêu cầu gửi lại.

## **3.5. Sự khuyến khích (Incentive)**

The quy ước, giao dịch đầu tiên trong khốilà giao dịch đặc biệt, khởi tạo đồng bitcoin mới cho người tạo ra khối giao dịch đó. Đây là sự khuyến khích mà hệ thống trao cho các node “ có công “ hỗ trợ nó, và cũng là 1 cách để phân phối đồng tiền vào lưu thông, khi không có 1 cơ quan tập trung nào phụ trách phát hành chúng.

Sự gia tăng ổn định của 1 lượng tiền nhất định vào thị trường cũng tương tự như những thợ vàng dùng các nguồn lực mà họ có để khai thác và đưa vàng vào thị trường. Trong thường hợp này, nguồn lực ở đây là thời gian tính toán của CPU và chi phí điện năng bỏ ra. Sự khuyến khích có thể cắt ra từ phí giao dịch. Khi số tiền đầu ra < giá trị đầu vào, số tiền chênh lệch được cộng dồn là số tiền khuyến khích của khối chứa giao dịch đó. Khi 1 số tiền định trước đã được đưa vào thị trường, tiền khuyến khích sẽ lấy toàn bộ từ phí giao dịch để tránh lạm phát xảy ra.

Tiền khuyến khích này cũng có tác dụng giữ các node trong mạng duy trì sự trung thực. Khi 1 kẻ tấn công có thể điều phối số lượng CPU nhiều hơn cả số node trung thực, anh ta có thể chọn giữa việc gian lận để đòi lại số tiền của mình hoặc dùng số máy này để khai thác ra coin mới. Anh ta sẽ thấy rằng tốt nhất là chơi theo luật, vì luật đó bảo vệ anh ta và sự làm giàu của anh ta là hợp pháp, được mọi người công nhận.

## **3.6. Lấy lại dung lượng ổ cứng (Reclaiming Disk Space)**

Khi giao dịch cuối cùng của 1 coin được chôn dưới 1 số khối xác định, các giao dịch cũ hơn sẽ được loại bỏ để tiết kiệm ổ cứng. Để tạo điều kiện cho việc này mà không phá vỡ chuỗi hàm băm, các giao dịch được lưu dưới dạng cây Merkle, chỉ có gốc là nằm trong mảng băm của khối. Các giao dịch cũ hơn được loại đi bằng cách cắt tỉa cành.


![](https://d2mxuefqeaa7sj.cloudfront.net/s_BC5C8AA54AA86AEBF7D7D4BDCD271C051B03A344DD960F842E0176C2079EAE55_1512380020072_file.png)


Hãy xem xét ví dụ về 1 khối giao dịch chứa 16 giao dịch từ A đến P, được lưu dưới dạng cây Merkle như hình vẽ dưới đây. So sánh với hình trên ( 4 giao dịch ), gốc của cây vẫn chỉ có kích thước là 32 byte, đây là kích thước không đổi kể cả khi số lượng giao dịch tăng nhanh. Việc chứng minh 1 giao dịch là tồn tại trong khối thực chất là việc tìm đường đi từ lá đến gốc. Việc kiểm tra được thực hiện bằng cách xây dựng lại đường đi từ lá đến gốc cây. Ví dụ để chứng minh HL có thuộc giao cây dưới đây hay không, ta kiểm tra đường xác thực gồm các nốt trên đường đi: Hkl, Hijkl, Hijklmop, và gốc. Đường xác thực ngày gồm 4 nốt, có chiều dài 128 bytes.

![](https://d2mxuefqeaa7sj.cloudfront.net/s_BC5C8AA54AA86AEBF7D7D4BDCD271C051B03A344DD960F842E0176C2079EAE55_1512380020110_file.jpeg)



Phần header của 1 khối không chứa giao dịch có kích thước khoảng 80 bytes. Giả sử 10 phút sẽ có 1 khối được sinh ra, dung lượng 1 năm là 4.2MB.


  **Bảng** **1: Kích thước khối có giao dịch được lưu theo cây Merkle.**

| **Số lượng giao dịch** | **Kích thước trung bình của các giao dịch** | **Chiều cao cây đường đi** | **Kích thước** |
| ---------------------- | ------------------------------------------- | -------------------------- | -------------- |
| 16                     | 4 kilobytes                                 | 4 lần băm                  | 128 bytes      |
| 512                    | 128 kilobytes                               | 9 lần băm                  | 288 bytes      |
| 2048                   | 512 kilobytes                               | 11 lần băm                 | 352 bytes      |
| 65,535                 | 16 megabytes                                | 16 lần băm                 | 512 bytes      |


Theo như bảng trên, trong khi kích thước của khối tăng rất nhanh từ 4KB cho 16 giao dịch, lên đến 16MB cho 65535 giao dịch, thì kích thước đường xác thực tăng không nhiều, chỉ từ 128 byte lên 512 byte ( gấp 4 lần ). Với cách lưu trữ này, 1 nốt chỉ cần download 1 khối header ( 80 byte ) sau đó xác thực 1 giao dịch có tồn tại trong khối hay không bằng cách trích ra 1 đường xác thực mà không cần phải lưu trữ toàn bộ hay truyền toàn bộ dữ liệu của khối, có thể lên đến vài gigabytes. Các nốt không duy trì toàn bộ chuỗi khối, được gọi nốt SPV ( cách xác minh thanh toán đơn giản ) sử dụng đường merkle để xác minh giao dịch mà không cần download dữ liệu của cả khối.


## **3.7. Cách xác minh thanh toán đơn giản (Simplified Payment Verification (SPV))**

Có thể xác minh giao dịch mà không phải chạy toàn bộ các nốt mạng. Người dùng chỉ cần lưu giữ header của các khối trong chain dài nhất, dữ liệu này có thể truy vấn từ các node khác cho đến khi người dùng chấp nhận chain mình có là dài nhất. Người dùng ưu cả dữ liệu đường Merkle chứa giao dịch được liên kết đến khối trong khoảng thời gian tương ứng. Người dùng không thể tự check giao dịch của chính mình nhưng bằng cách liên kết nó vào chain, anh ta có thể thấy rằng các node mạng khác đã chấp nhận giao dịch đó, giao dịch đã được thêm vào khối.

![](https://d2mxuefqeaa7sj.cloudfront.net/s_BC5C8AA54AA86AEBF7D7D4BDCD271C051B03A344DD960F842E0176C2079EAE55_1512380020025_file.jpeg)


Với cách thức này, việc xác thực là đáng tin cậy cho đến khi các nút mạng trung thực còn kiểm soát được. Với phương thức các nốt mạng tự xác thực giao dịch 1 cách đơn giản như vậy, nó có thể bị lừa khi kẻ tấn công chiếm quyền mạng và tạo ra hàng loạt các giao dịch giả mạo. Cách xử lý là cho phép các nút mạng cảnh báo khi nó nhận được các khối không hợp lệ, khiến phần mềm tải lại toàn bộ khối và gắn cảnh báo các giao dịch gây ra sự không nhất quán. Các doanh nghiệp thường nhận được giao dịch thanh toán thường xuyên vẫn muốn chạy hệ thống riêng để đảm bảo sự bảo mật và xác thực nhanh.


## **3.8 .Kết hợp và tách giá trị**

Mặc dù hệ thống có thể xử lý riêng từng đồng tiền nhưng thông thường không ai tạo từng giao dịch cho mỗi cent chi tiêu. Hệ thống cho phép tách coin và kết hợp thành các giao dịch nhiều đầu vào và đầu ra. Đầu vào có thể là 1 giao dịch có giá trị cao trước đó, hoặc rất nhiều giao dịch giá trị nhỏ, đầu ra gồm 2 loại, cho người nhận và phần tiền thừa trả lại cho sender.

![](https://d2mxuefqeaa7sj.cloudfront.net/s_BC5C8AA54AA86AEBF7D7D4BDCD271C051B03A344DD960F842E0176C2079EAE55_1512380020033_file.jpeg)

##  **3.9 Tính riêng tư**

Trong mô hình ngân hàng truyền thống, tính riêng tư được duy trì bằng cách hạn chế việc tiếp cận thông tin từ các bên liên quan và từ bên thứ 3. Khi cần công khai thông tin giao dịch họ vẫn duy trì bằng cách sử dụng các khóa công cộng vô danh. Mọi người có thể thấy ai đó đã gửi tiền cho người nào đó, nhưng thực sự không có thông tin liên kết giữa giao dịch với 1 người xác định. Điều này cũng tương tự như mức độ thông tin công khai ở thị trường chứng khoán.

Với bitcoin, 1 tường lửa bổ sung – cặp khóa dược dùng trong mỗi giao dịch sẽ giúp liên kết giao dịch với các chủ sở hữu ( người gửi và người nhận ). Trong giao dịch nhiều đầu vào thì sẽ có nhiều liên kết, điều này là cần thiết để xác minh các đầu vào này cùng thuộc 1 chủ sở hữu. Rủi ro xảy ra là nếu chủ sở hữu của khóa bị tiết lộ, các liên kết đến giao dịch của họ cũng bị tiết lộ.




# **4. Các ứng dụng của công nghệ chuỗi khối đang thay đổi xã hội**

### **4.1 Chuỗi khối kinh doanh, dịch vụ tài chính**

Các hệ thống truyền thống thường hay công kềnh, gặp nhiều lỗi và rất chậm chạm. Các bên trung gian luôn cần thiết để có thể dàn xếp các quy trình và giải quyết xung đột. Một cách tự nhiên, điều này gây ra căng thẳng, tốn thời gian và tiền của. Ngược lại, những người dùng thấy rằng chuỗi khối rẻ hơn, minh bạch hơn và hiệu quả hơn. Một số các dịch vụ tài chính đang sử dụng hệ thống này để mang đến sự đổi mới, ví dụ như [smart bonds](http://smartbonds.co/) và [smart contracts](https://blockgeeks.com/guides/smart-contracts/). Smart bonds tự động thanh toán phiếu giảm giá cho người dùng khi các điều kiện cho trước được hoàn thành. Smart contracts là các hợp đồng số được tự thực hiện, tự bảo trì khi các điều kiện cho trước được hoàn thành.

Ví dụ về các dịch vụ tài chính chuỗi khối:

***- Quản lý tài sản: Quy trình buôn bán và thanh toán***

Quy trình buôn bán truyền thống với việc quản lý tài sản (khi các bên trao đổi và quản lý tài sản) có thể rất tốn kém và nhiều rủi ro, nhất là khi đó là các giao dịch xuyên biên giới. Mỗi bên trong quá trình này, ví dụ như người môi giới, người trông coi tài sản, người quản lý thanh toán, giữ các bản ghi của riêng họ, điều này tạo ra sự thiếu hiệu quả rõ rệt và chứa đầy những lỗi. Cuốn sổ cái của chuỗi khối giúp giảm lỗi bằng cách mã hoá các bản ghi, đồng thời đơn giản hoá quy trình, và bỏ qua sự cần thiết của các bên trung gian.

***- Bảo hiểm: Quy trình yêu cầu***

Quy trình yêu cầu là một quy trình gây ra nhiều sự bực dọc và bạc bẽo. Những nhân viên bảo hiểm cần phải lội qua những yêu cầu lừa đảo, các nguồn dữ liệu phân mảnh, hoặc các quy tắc đã bị bỏ đi đối với người dùng tạo đưa ra một số ít các form và xử lý chúng một cách thủ công. Điều này chứa đầy những lỗi. Chuỗi khối cung cấp một hệ thống hoàn hảo cho việc quản lý minh bạch và không mạo hiểm. Những tài liệu đã được mã hoá cho phép nhân viên bảo hiểm nắm được quyền làm chủ của các tài sản sẽ được bảo hiểm.

***- Thanh toán: Thanh toán xuyên biên giới***

Việc thay toán quốc tế chứa nhiều lỗi, tốn kém và dễ gây ra rửa tiền. Nó tốn ít nhất vài ngày cho việc chuyển tiền quốc tế. Chuỗi khối đã và đang cung cấp các giải pháp cho các công ty chuyển tiền như Abra, Align Commerce và Bitspark bằng việc đưa ra các dịch vụ chuyển tiền dựa trên chuỗi khối đầu cuối. Vào năm 2016, Santander trở thành một trong những ngân hàng đầu tiên sử dụng chuỗi khối trong một ứng dụng thanh toán, cho phép các khách hàng thực hiện chuyển tiền quốc tế 24/24 và hoàn thành vào ngày hôm sau.

### **4.2 Tài sản thông minh**

Một tài sản vô hình hay hữu hình, như những chiếc ô tô, toà nhà, nồi cơm điện hay là các bằng sáng chế, tên tài sản hay cổ phần công ty, đều có thể được nhúng bởi các công nghệ thông minh. Những sự đăng ký như vậy, có thể được lưu trữ trong sổ cái cùng với các thông tin hợp đồng của những người cho phép quyền sở hữu của tài sản. Khoá thông minh (smart keys) có thể được sử dụng để cung cấp quyền truy cập cho các bên được cho phép. Và cuốn sổ cái sẽ là nơi lưu giữ và cho phép sự trao đổi của các khoá thông mình này một khi hợp đồng đã được xác nhận.
Cuốn sổ cái phân tán cũng trở thành một hệ thống để lưu lại và quản lý các quyền cho tài sản cũng như là cho phép sao chép các hợp đồng thông mình trong trường hợp khoá thông minh bị mất.
Sử dụng "tài sản thông minh" giúp bạn hạn chế được rủi ro của việc bị lừa đảo, giảm phí trung gian và các tình huống khó khăn trong giao dịch. Cùng với đó, tăng cường sự hiệu quả và sự tín nhiệm.

Ví dụ về tài sản thông minh:

***- Cho vay phi thường / cho vay thế châp***

***- Xe hơi / điện thoại thông minh***

***- Chuỗi khối Internet-of-Things (IoT)***

### **4.3 Chuỗi khối sẽ đi về đâu**

Trong tất cả các trường hợp, cuốn sổ cái chuỗi khối cung cấp sự bảo mật cho Internet of things. Với hàng tỉ nhữ thiết bị liên kết với nhau, các nhà an ninh mạng có lý do để lo lắng về vấn đề bảo mật đối với hệ thống dữ liệu phân tán.
Các công ty có thể làm gì để bảo vệ hệ thống của họ khỏi bị tấn công?

- Các nhà phát minh sẽ bảo vệ ý tưởng của họ như thế nào?
- Các chính phủ sẽ bảo vệ các thông tin mật khỏi gián điểm và chủ nghĩa khủng bố ra sao?

Trên đây là các vấn đề làm thế nào để sắp xếp và phân tích lượng dữ liệu khổng lồ đến tự các thiết bị liên quan. Việc truy cập vào hệ thống sổ cái chuỗi khối chỉ được chấp nhận đối với các bên được tín nhiệm. Cuốn sổ cái cung cấp cho các bên một nền tảng quản lý để có thể phân tích một lượng dữ liệu khổng lồ.

Các ví dụ về chuỗi khối Internet-of-Things (IoT):

***- Thiết bị thông minh***

***- Cung cấp các chuỗi cảm biến***

### **4.4 Hợp đồng thông minh**

Hợp đồng thông mình là các kỹ thuật số được nhúng bởi một đoạn code if-this-then-that (IFTTT), cho phép chúng tự thực thi. Trong thực tế, một bên trung gian bảo đảm rằng tất cả các bên liên quan đều tuân thủ các điều khoản. Chuỗi khối không cần bên thứ ba, nhưng nó cũng bảo đảm rằng tất cả các bên tham gia đều biết được chi tiết hợp đồng và các điều khoản sẽ được tự động thực hiện một khi các điều kiện được bảo đảm.

Bạn có thể sử dụng hợp đồng thông minh cho tất cả các tình huống, như các dẫn xuất tài chính, phí bảo hiểm, luật tài sản và các sự đồng thuận đóng góp quỹ giữa các cá nhân, tổ chức.

***- Dịch vụ chăm sóc sức khoẻ chuỗi khối***

***- Âm nhạc chuỗi khối***

***- Chính phủ chuỗi khối***

Ví dụ về Chính phủ chuỗi khối

- Giá trị công cộng / cộng đồng
- Trách nhiệm được giao phó
- Định danh chuỗi khối

### **4.5 Chuỗi khối bảo vệ danh tính của bạn bằng cách mã hoá và bảo vệ nó khỏi những spammer và các nhân viên marketing**

Ví dụ về định danh chuỗi khối

***- Hộ chiếu***

***- Chứng nhận sinh, tử, kết hôn***

***- Định danh cá nhân***

# **5. Chuỗi khối có thể giúp gì cho chuỗi cung ứng?**
[Chuỗi cung ứng](https://en.wikipedia.org/wiki/Supply_chain) (Supply Chain) [3] là một hệ thống các tổ chức, con người, hoạt động, thông tin và các nguồn lực liên quan tới việc chuyển sản phẩm hay dịch vụ từ nhà cung cấp (chuỗi cung ứng) đến khách hàng. Hoạt động chuỗi cung ứng liên quan đến chuyển đổi các tài nguyên thiên nhiên, nguyên liệu và các thành phần thành một sản phẩm hoàn chỉnh để giao cho khách hàng cuối cùng.
##  **5.1 Hệ thống theo dõi dữ liệu không lỗi, giúp quản lý chuỗi cung ứng tốt hơn**

Công nghệ chuỗi khối không cần máy quét hoặc bất cứ thiết bị nào tương tự để xác thực thông tin, nó có thể tự động lưu lại dữ liệu mọi thể loại về sản phẩm. Không còn phải lo lưu trữ tài liệu giấy, không còn cần những báo cáo thủ công. Chuỗi khối lưu lại mọi sự tương tác dù là nhỏ nhất trong suốt chiều đi của sản phẩm. Dữ liệu không hề bị ảnh hưởng, dù có vấn đề gì xảy ra với hệ thống.

![](https://viblo.asia/uploads/443ef8fa-bbe3-4a58-a53b-466bc037778d.png)


Bây giờ, bạn có thể cắt bỏ những chi phí lưu trữ hành chính khổng lồ mà vẫn đảm bảo tính xác thực cao của dữ liệu, từ đó quản lý và dự đoán rủi ro tốt hơn.

## **5.2 Xây dựng cơ sở dữ liệu tin cậy và an toàn, tăng cường tính minh bạch trong chuỗi cung ứng**

Với chuỗi khối, dữ liệu một khi đã được xác thực và lưu lại sẽ không thể thay đổi hay đánh cắp. Điều này có được nhờ các kết nối thông minh với một số điều kiện mã hoá được yêu cầu để xác nhận tính hợp lệ và cho phép hoàn tất giao dịch. Bạn sẽ thấy rằng chuỗi khối có thể ngăn chặn những tiêu cực thường thấy trong cơ sở dữ liệu truyền thống, ví dụ như việc khai khống dữ liệu vì mục đích cá nhân. Ngoài ra, với yêu cầu xác thực duy nhất để tương tác với chuỗi khối, những lỗ hổng bảo mật đã được giảm đến mức tối thiểu.

![](https://viblo.asia/uploads/60250591-16b3-4ea6-9089-2ac99de6f90b.png)


Với quyền truy cập rộng mở cho cả mạng lưới, các thành viên giờ đây có quyền bình đẳng chia sẻ dữ liệu. Điều này giúp tăng sự tin tưởng giữa các nhà cung cấp trong chuỗi cung ứng và từ đó, tạo nên sự hợp tác chặt chẽ hơn trong cả hệ thống. Không chỉ thế, doanh nghiệp có thể lấy được sự tin tưởng nhiều hơn từ khách hàng bằng cách show ra tiến trình sản xuất sản phẩm, từ đó tăng lợi thế cạnh tranh.

## **5.3 Tăng năng suất làm việc, đơn giản hóa việc tìm lỗi trong chuỗi cung ứng**

Khi lòng tin và sự minh bạch đã được hình thành, tất cả những tương tác liên quan đến sản phẩm đều trở nên nhanh chóng và thông suốt hơn, từ đó tăng năng suất và sản lượng giao dịch.
Lợi ích của chuỗi khối không chỉ dừng lại ở đó. Khi các giao dịch được lưu trữ trong cơ sở dữ liệu có phân cấp và theo thứ tự thời gian, việc theo dõi lỗi trở nên thật đơn giản. Nó cũng giúp các nhà quản lý chuỗi cung ứng phản ứng kịp thời với các sự cố xảy ra trong chuỗi. Quay lại trường hợp của Chipotle, nếu họ sử dụng chuỗi khối để theo dõi nguồn cũng như chất lượng của nguyên liệu thô, họ đã có thể phát hiện ra vi khuẩn E. coli sớm hơn, loại bỏ các thành phần bị nhiễm bệnh trước khi bán chúng cho khách hàng.
Trường hợp của Chipotle đã trở thành một lời cảnh tỉnh không chỉ đối với các nhà hàng mà cả các công ty FMCG. Việc theo dõi sản phẩm từ khi xuất ra đang ngày càng thu hút sự chú ý của các ông lớn. [Đầu năm nay, Walmart đã bắt đầu áp dụng công nghệ trong việc theo dõi sản xuất thịt lợn ở Mỹ và Trung Quốc](https://blogs.wsj.com/cio/2016/12/16/wal-mart-readies-blockchain-pilot-for-tracking-us-produce-china-pork/)[4]. [Co-op cũng là siêu thị đầu tiên tiên phong nâng cao tính xác thực của thực phẩm với chiến dịch “công bằng thương mại trong thời đại số”](http://www.cityam.com/248873/co-op-exploring-blockchain-technology)[5]

# **6. Ứng dụng trên Ethereum chuỗi khối**
## **6.1 Giới thiệu ứng dụng**
Đây là ứng dụng câu hỏi trắc nghiệm đơn giản trên nền tảng Ethereum - ứng dụng phi tập trung (decenterlized app). Mỗi tài khoản sẽ có một khoản tiền. Với mỗi tài khoản người dùng có thể thêm câu hỏi trắc nghiệm vào ngân hàng câu hỏi. Để tăng giá trị tài khoản người dùng cần trả lời câu hỏi trắc nghiệm trong ngân hàng các câu hỏi. Nếu trả lời đúng tiền của tài khoản tạo ra câu hỏi đó sẽ chuyển đến tài khoản của bạn và ngược lại khi bạn trả lời sai.
### Code:  https://github.com/vuhoanglinh96/food

Cài đặt testrpc: [https://github.com/ethereumjs/testrpc](https://github.com/ethereumjs/testrpc)

Chạy testrpc:


     testrpc -m 'tuna move mistake token flush accident hazard dish coral try usual sell'



Khi clone git project về, chạy lệnh:

    npm install
    truffle compile
    truffle migrate

Chạy server local:

    ng serve



Chạy server backend:

    cd backend
    npm install
    npm run start

## **Giao diện ứng dụng**
- Thêm câu hỏi
![Thêm câu hỏi](https://d2mxuefqeaa7sj.cloudfront.net/s_D92D9A08DD3D3A7D7C3336B6DF64C5DFE3450EC0AE94A625584E9675621CB858_1511583662538_1.jpg)

- Trả lời câu hỏi
![Trả lời câu hỏi](https://d2mxuefqeaa7sj.cloudfront.net/s_D92D9A08DD3D3A7D7C3336B6DF64C5DFE3450EC0AE94A625584E9675621CB858_1511583685584_2.jpg)

- Khi hết câu hỏi
![Màn hình hết câu hỏi](https://d2mxuefqeaa7sj.cloudfront.net/s_395487EF645AFB7E75DF51F504223E63C12B2A41CEA40E9654E4382AEA3086D3_1511947870437_Screenshot+2017-11-29+15.57.06.png)

- Khi hết tiền
![Màn hình hết tiền](https://d2mxuefqeaa7sj.cloudfront.net/s_395487EF645AFB7E75DF51F504223E63C12B2A41CEA40E9654E4382AEA3086D3_1511947961956_Screenshot+2017-11-29+15.57.35.png)


## **6.2 Các công nghệ**
## **Ethereum**

[Ethereum (ETH)](https://blogtienao.com/ethereum-la-gi/) [6] hay còn được gọi là Bitcoin 2.0, là một nền tảng điện toán phân tán khối chuỗi, chạy trên chuỗi khối, thông qua việc sử dụng chức năng Hợp đồng thông minh (Smart Contract). Tiền ảo Ethereum có thể thực hiện các giao dịch, hợp đồng mạng ngang hàng thông qua đơn vị tiền ảo là Ether. Không những thế, ETH còn được đánh giá là một nền tảng ứng dụng hữu ích, và tự tạo ra hệ sinh thái tài chính phân tán cho riêng mình.

## **Hợp đồng thông minh**

Hợp đồng thông minh (Smart contracts)[7] về cơ bản nó là một thuật toán khi có điều kiện cho trước được đáp ứng đầy đủ thì các điều khoản hợp đồng sẽ được thực thi một cách tự động, mà không cần sự can thiệp của con người, hay nói cách khác nó là những ứng dụng được lưu trữ trong chuỗi khối. Công nghệ này ra đời cho phép “cuốn sổ cái” theo dõi và ghi lại mọi hoạt động giao dịch, thỏa thuận liên quan.

## **TestRPC**

[TestRPC](https://github.com/ethereumjs/testrpc) [8] là một khách hàng Ethereum dựa trên Node.js để thử nghiệm và phát triển. Nó sử dụng ethreumjs để mô phỏng đầy đủ các hành vi của khách hàng và làm cho các ứng dụng Ethereum đang phát triển nhanh hơn. Nó cũng bao gồm tất cả các chức năng và tính năng phổ biến RPC (như các sự kiện).
*TestRPC* đơn giản chỉ là một mạng chuỗi khối chạy trên máy local của chúng ta; thường được sử dụng để chạy test cho hợp đồng thông ming và các DApp trên local. Ngoài ra, chúng ra có thể triển khai trên các public network như [Ropsten](http://pool.ropsten.ethereum.org/), [Kovan](https://kovan.etherscan.io/) hay thậm trí là trên testnet của Ethereum luôn.

## **Truffle framework**

[Truffle](http://truffleframework.com/docs/) [9] là một framework phát triển phổ biến nhất cho Ethereum. Với Truffle bạn sẽ có:

- Hợp nhất biên dịch hợp đồng thông minh, liên kết, triển khai và quản lý nhị phân.
- Thử nghiệm hợp đồng tự động để phát triển nhanh hơn.
- Scriptable, extensible deployment & migrations framework.
- Quản lý mạng để triển khai đến bất kỳ số mạng công cộng và riêng.
- Quản lý gói với EthPM & NPM, sử dụng tiêu chuẩn ERC190.
- Giao diện điều khiển tương tác để giao tiếp hợp đồng trực tiếp.
- Cấu hình xây dựng đường ống với sự hỗ trợ tích hợp chặt chẽ.
- Người chạy tập lệnh bên ngoài thực hiện các tập lệnh trong môi trường Truffle.

## **Nodejs**

[Node.js](https://nodejs.org) [10] là một mã nguồn mở, được xây dựng dựa trên nền tảng Javascript V8 Engine Node.js có thể chạy trên nhiều nền tảng hệ điều hành khác nhau từ Window cho tới Linux, OS X nên đó cũng là một lợi thế. Nó cung cấp các thư viện phong phú ở dạng JavaScript Module khác nhau giúp đơn giản hóa việc lập trình và giảm thời gian ở mức thấp nhất.

## **Angularjs**

[Angular](https://angularjs.org/) [11] là một nền tảng phát triển để xây dựng các ứng dụng di động hoặc ứng dụng web. Angular hoàn toàn miễn phí, được phát triển bởi Google, nó tạo ứng dụng dựa trên HTML và JavaScript hoặc một ngôn ngữ có thể dịch sang JavaScript (như Dart hoặc TypeScript). Trên tất cả Angular nổi bật lên bởi các tính năng như đa nền tảng, tốc độ và hiệu năng cao, hỗ trợ phát triển toàn diện.

## **6.3 Cài đặt môi trường phát triển**

Để cài đặt TestRPC và Truffle thì trước tiên chúng ta cần có vài thứ sau đây:

- [Node.js v6+ LTS and npm (comes with Node)](https://nodejs.org/en/)
- [Git](https://git-scm.com/)

Sau đó, chúng ta tiến hành cài đặt TestRPC và Truffle.

    npm install -g ethereumjs-testrpc
    npm install -g truffle
## **Tạo một Truffle project**

Như đã đề cập ở trên, Truffle có một số dự án mẫu nên chúng ta có thể dễ dàng khởi tạo một dự án mới dựa trên những dự án mẫu đã có sẵn bằng cách sử dụng `truffle unbox`

    // Tạo thư mục.
    mkdir name-tutorial

    //Điều hướng đến thư mục.
    cd name-tutorial

    //Khởi tạo Truffle
    truffle unbox name

Ngoài ra chúng ra có thể khởi tạo một ứng dụng Truffle rỗng bằng cách sử dụng lệnh `truffle init bare`.


## **Cấu trúc thư mục ứng dụng**

Cấu trúc một ứng dụng Truffle cơ bản bao gồm các thành phần sau:

- /contracts: chứa những file mã nguồn [Solidity](https://solidity.readthedocs.io/en/develop/) mô tả các hợp đồng thông minh của ứng dụng.
- /migrations: Truffle sử dụng migration để xử lý triển khai hợp đồng thông minh. Một migration là một hợp đồng thông minh đặc biệt bổ sung để theo dõi các thay đổi.
- /test: chứa Javascript và *Solidity* code test cho các hợp đồng thông minh.
- truffle.js: thư mục cấu hình của Truffle

## **Định nghĩa một hợp đồng thông minh**

Chúng ta sẽ phát triển một ứng dụng phân tán, DApp, bằng cách định nghĩa một hợp đồng thông minh ****đóng vai trò như là một xử lý logic nghiệp vụ và lưu trữ ở phía *back-end*.
Trước tiên chúng ta tạo một file  `Metacoin.sol` trong thư mục `/contracts` với nội như sau

    pragma solidity ^0.4.4;

    contract Metacoin {
      mapping (address => uint) balances;

    	event Transfer(address indexed _from, address indexed _to, uint256 _value);

    	function MetaCoin() {
    		balances[tx.origin] = 10000000000;
    	}

    	function sendCoin(address receiver, uint amount) returns(bool sufficient) {
    		if (balances[msg.sender] < amount) return false;
    		balances[msg.sender] -= amount;
    		balances[receiver] += amount;
    		Transfer(msg.sender, receiver, amount);
    		return true;
    	}

    	function getBalanceInEth(address addr) returns(uint){
    		return ConvertLib.convert(getBalance(addr),2);
    	}

    	function getBalance(address addr) returns(uint) {
    		return balances[addr];
    	}

    }

Có hai thứ quan trọng các bạn cần chú ý ở đoạn code trên

1. Phiên bản tối thiểu của Solidity được định nghĩa ở trên cùng `pragma solidity ^0.4.4;`
2. Giống như hầu hết các ngôn ngữ lập trình khác, `Solidity` sử dụng dấu `;` là ký tự phân cách các dòng lệnh.
    Solidity là một ngôn ngữ lập trình có static-type, nên chúng ta bắt buộc phải khai báo kiểu dữ liệu cho các tham biến có kiểu như string, int hay array. Ngoài ra, Solidity có thêm một kiểu dữ liệu đặc thù là address độ dài 20 bytes dùng để lưu trữ địa chỉ trên Ethereum chuỗi khối. Các tài khoản hay hợp đồng thông minh trên Ethereum chuỗi khối đều có một địa chỉ đến có thể gửi/nhận dữ liệu đi đến những địa chỉ đó.


## **Biên dịch và migration hợp đồng thông minh**

**Biên dịch**

*Solodity* là một ngôn ngữ biên dịch, nên chúng ta cần dịch mã nguồn ra bytecode để có thể chạy trên `EVM`.  Rồi deploy lên chuỗi khối để chúng ta có thể tương tác với hợp đồng thông minh đã định nghĩa.
Trước tiên, chúng ta mở một cửa sổ Terminal mới rồi chạy lệnh testrpc  'tuna move mistake token flush accident hazard dish coral try usual sell'  để khởi động một chuỗi khối ở local. Màn hình Terminal có thể sẽ như sau:


    EthereumJS TestRPC v6.0.3 (ganache-core: 2.0.2)

    Available Accounts
    ==================
    (0) 0x387908fd4f030c94f7f28ad61b1386d56c12f162
    (1) 0x4b7dafb95151f8ec334ba610bc74bb33ba7298c3
    (2) 0xaca73543a32387bee98dab5237d00a4e78593b64
    (3) 0x6e700ca0a5add1b1111c2893d070eb3e17435ba9
    (4) 0xf67f44504dceed2f41acff4e9e6fd996fed17c34
    (5) 0x199847c004ee018bee7ad21435bbdac32c961b08
    (6) 0xf669b282e0a5d28f5f809f2bc43988c5e2f07f96
    (7) 0x18237c75e8cc0bbf1d0f1221323b6641d1a7f098
    (8) 0x20f6753663f3d05315939315876ff3ce181564f0
    (9) 0xfbdb2bc8a3abf41a8cb8b9968e7023313e917f72

    Private Keys
    ==================
    (0) 4a4163a7f753004ee6cb8c9c6d80329d6636f2471067a26a9c0b1734e285efe6
    (1) d1595fa85be6fa4bdd249246ba8090de917351a170cdd1746b4ea5998a76c9bc
    (2) fd64432b991782817acd82c54c29a98835aec1094e973baf376613b2072b7edd
    (3) aa9089028901e5f77601ff4e7b8493a23a146bb1bd285d03ff68b3513d6f1486
    (4) 5228f82697f9bea494788802a42ea75b83e41a1adabc4108ba6076533068cdb2
    (5) 9259ad0d01b3d52828e29c23abfe76c6106245efcfd4bd4db757527b520ae092
    (6) 4b2c3da6e654bb81c549e287323c7df8f646f2ba8105a02222850ff97c36957b
    (7) 25f395d3ad4e33976bc0de4e2880ba02e503e7036fed96142a0a5287bdb3d1ae
    (8) 1a3038f5fec7070a9e09a92b16433029cb1bff57e221e65f10732f4b55d6ab42
    (9) 53216096ca64520258a219a550e9c487d8350df168be4553a83cb16ea417819b

    HD Wallet
    ==================
    Mnemonic:      tuna move mistake token flush accident hazard dish coral try usual sell
    Base HD Path:  m/44'/60'/0'/0/{account_index}

    Listening on localhost:8545


**Migration**

Sau khi đã biên dịch thành công hợp đồng thông minh ở bước trên, bây giờ chúng ta thực hiện migration hợp đồng thông minh lên chuỗi khối. Migration là một mã code để deploy và thay đổi trạng thái của hợp đồng ứng dụng của chúng ra. Ở lần migration đầu tiên thì chỉ đơn giản là deploy code mới lên chuỗi khối. Còn các lần migration sau, ngoài việc deploy hợp đồng mới thì còn bao gồm cả việc migration các dữ liệu cũ cho phù hợp với hợp đồng thông minh mới.

Migrate dữ liệu lên mạng chuỗi khối


    var ConvertLib = artifacts.require("./ConvertLib.sol");
    var MetaCoin = artifacts.require("./MetaCoin.sol");

    module.exports = function(deployer) {
    deployer.deploy(ConvertLib);
    deployer.link(ConvertLib, MetaCoin);
    deployer.deploy(MetaCoin);
    };

## **Kết nối tới mạng chuỗi khối sử dụng web3**


    constructor(private windowRef : WindowRefService) {
    this.MetaCoin = contract(metacoin_artifacts);
    this.checkAndRefreshWeb3();
    }
    private checkAndRefreshWeb3() {
      if (this.ready) {
        this.refreshAccounts();
        return;
      }

    this.web3 = new Web3(new Web3.providers.HttpProvider('http://localhost:8545'));
    var jwt = localStorage.getItem('id_token');
    var address = localStorage.getItem('address');
    if (!address) return;
    var decodedJwt = this.jwtHelper.decodeToken(jwt);
    console.log(address);
    this.MetaCoin.setProvider(this.web3.currentProvider);
    this.refreshAccounts();
    };


## **Hàm chuyển tiền**



    public sendEth(sender, receiver) {
      this.web3 = new Web3(new Web3.providers.HttpProvider('http://localhost:8545'));
      var amount = this.web3.toWei(3, "ether");
      this.web3.eth.sendTransaction({from:sender, to:receiver, value: amount})
    }


**Tài liệu tham khảo**

[1] https://vi.wikipedia.org/wiki/Blockchain#cite_note-fortune20160515-2

[2] https://vi.wikipedia.org/wiki/Bitcoin

[3] https://en.wikipedia.org/wiki/Supply_chain

[4] https://blogs.wsj.com/cio/2016/12/16/wal-mart-readies-blockchain-pilot-for-tracking-us-produce-china-pork/

[5] http://www.cityam.com/248873/co-op-exploring-blockchain-technology

[6] https://blogtienao.com/ethereum-la-gi/

[7] https://blogtienao.com/ethereum-la-gi/

[8] https://github.com/ethereumjs/testrpc

[9] http://truffleframework.com/docs/

[10] https://nodejs.org

[11] https://angularjs.org/
