# Blockchain
## BLockchain là gi ?
```
    Blockchain là hệ thống cơ sở dữ liệu cho phép lưu trữ và truyền tải các khối thông tin (block) được liên kết với nhau nhờ mã hóa.Các khối thông tin này hoạt động độc lập và có thể mở rộng theo thời gian. Chúng được quản lý bởi những người tham gia hệ thống chứ không thông qua đơn vị trung gian.
```
## Tại sao blockchain lai bảo mật 
### Mạng ngang hàng (P2P) :
- Mạng ngang hàng-P2P là một mô hình giao tiếp phi tập trung giữa hai mạng ngang hàng hay còn được gọi là các node, có thể giao tiếp với nhau mà không cần máy chủ trung tâm.
- Mỗi node giữ một bản sao của các tệp, đóng vai trò là máy khách và máy chủ cho các node khác.
- Các loại P2P:
    - **Unstructured P2P Networks**: 
        - Đây là loại mạng P2P mà trong đó, các node được thiết lập ngẫu nhiên. Loại mạng này có khả năng chống lại việc một số node thường xuyên tham gia và rời khỏi mạng.
        - Ví dụ: Một nền tảng xã hội được triển khai trên mạng P2P không có cấu trúc có thể sử dụng nó một cách hiệu quả, vì người dùng có thể chọn tham gia hoặc rời khỏi mạng thường xuyên.

        - Tuy nhiên, dù dễ xây dựng hơn mạng P2P có cấu trúc nhưng chúng lại sử dụng bộ nhớ và CPU cao hơn. Vì khi tìm kiếm một nội dung, yêu cầu tìm kiếm sẽ được truyền trên cả mạng để tìm ra càng nhiều máy chia sẻ càng tốt. Điều này khiến mạng có thể luôn tràn ngập các yêu cầu tìm kiếm. Bên cạnh đó, mạng P2P không cấu trúc không thể đảm bảo việc tìm kiếm một nội dung sẽ sẽ thành công
    - **Structured P2P Networks**:
        - Đây là loại mạng ngang hàng mà các node được xây dựng theo một cấu trúc cụ thể. Cho phép các node tìm kiếm tệp nhanh chóng, ngay cả khi nội dung đó không phổ biến.

        - Bên cạnh đó, mạng P2P có cấu trúc đã sử dụng hệ thống DHT (Distributed Hash Table) để khắc phục nhược điểm có thể tìm kiếm không thành công của mạng P2P không cấu trúc.

        - Tuy mang lại hiệu quả cao nhưng mạng P2P có cấu trúc lại có mức độ tập trung cao hơn. Ngoài ra mức chi phí thiết lập cùng bảo trì cũng cao hơn.


    - **Hybrid P2P Network**:
        - Đây là loại mạng P2P kết hợp giữa cấu trúc truyền thống (máy chủ và máy khách) cùng cấu trúc mạng ngang hàng.
        - Chức năng tập trung được cung cấp bởi mạng có cấu trúc và sự bình đẳng của node được cung cấp bởi mạng không có cấu trúc đã tạo ra sự cân bằng trên mạng kết hợp.
        So với hai loại mạng P2P trên thì mạng kết hợp dễ xây dựng hơn. Ngoài ra chúng còn thừa hưởng tất cả các ưu điểm và hiệu suất hoạt động cũng tốt hơn.
### Proof-of-Work
- Cơ chế đồng thuận được thiết kế để giải quyết vấn đề lòng tin giữa những người tham gia mạng blockchain
- Khi thực hiện giao dịch trên Blockchain, nó sẽ được gom vào một Block cùng một số giao dịch khác. Các thợ đào sẽ sử dụng hệ thống máy đào gồm nhiều máy tính mạnh để xác minh giao dịch.
- Một câu đố toán học phức tạp sẽ được hệ thống đưa ra. Nhiệm vụ của thợ đào là sử dụng sức mạnh của hệ thống đào tìm ra câu trả lời, sau khi tìm được sẽ thông báo cho các thợ đào còn lại. Khi phần lớn thành viên xác nhận đó là câu trả lời đúng, Block mới sẽ được tạo ra, giao dịch được xác nhận.
- Khi hoàn thành, thợ đào sẽ nhận được phần thưởng là phí giao dịch và phần thưởng khối. Nói một cách ẩn dụ, quá trình trên được gọi là “mining” (“khai thác”). Tuy nhiên, để quy tắc “longest-chain-wins” hoạt động an toàn, việc thêm các khối mới vào Block được thiết kế khá khó – tức là vừa tốn kém vừa mất thời gian. 

- Một vấn đề là PoW đòi hỏi nhiều lần thử lặp đi lặp lại – tiêu tốn sức mạnh tính toán đáng kể. Như Sam Beckett đã nói, vấn đề chủ yếu xoay quanh việc “try again, fail again, fail better” (tạm dịch: thử lại, thất bại lần nữa, thất bại nhưng đã tốt hơn). 
###  Proof-of-Stake
- Cũng giống như Proof-of-Work, Proof-of-Stake được thiết kế để đạt được sự đồng thuận phân tán về thứ tự hợp lệ của các giao dịch.
- Trong các blockchain sử dụng Proof-of-Stake, các node trong mạng tham gia vào việc xác thực các block (khối), thay vì phân bổ tài nguyên máy tính để “khai thác” chúng. 
- Tiền điện tử Ether (ETH) là một ví dụ điển hình về một dự án hiện đang trong quá trình chuyển đổi từ blockchain Proof-of-Work sang blockchain Proof-of-Stake.
# NFT là gì ?
- NFT là một loại tài sản kỹ thuật số có chứa thông tin về quyền sở hữu được lưu giữ trên blockchain. NFT được dùng để xác thực kỹ thuật số các món hàng như tác phẩm nghệ thuật, vật phẩm game,...  được lưu giữ trên mạng blockchain Etherum, Solana, … 
- Sự hình thành, phát triển và tiềm năng của mô hình Play to Earn. Người dùng có thể vừa tham gia trò chơi vừa có cơ hội kiếm được các vật phẩm NFT để kiểm tiến. Ngoài ra các nghệ sĩ, họa sĩ, nhà phát triển game… token hóa thành quả lao động của mình. 
- Nơi lưu trư:
    - Tạo Token ERC-721 đến từ việc lưu trữ các tài sản cơ bản. Nếu lưu trữ trực tiếp trên blockchain thì chi phí quá lớn 
    - IPFS là viết tắt của từ Interplanetary File System, một hệ thống tập tin phân tán ngang hàng kết nối tất cả các thiết bị máy tính với nhau.
    - IPFS là mạng phi tập trung ngang hàng cho phép người dùng sao lưu các tệp và trang web bằng cách lưu trữ chúng trên nhiều trang.
    - Điều này đảm bảo rằng nội dung có khả năng chống lại sự kiểm duyệt và các điểm lỗi tập trung như sự cố máy chủ hoặc các cuộc tấn công phối hợp.
# Metaverse là gì? 
    Metaverse là một môi trường kỹ thuật số hoạt động trên blockchain. Tại đây, các công nghệ như VR và AR đóng vai trò cung cấp thành phần trực quan, còn phương tiện phi tập trung cung cấp cơ hội kinh doanh và tương tác xã hội không giới hạn. Những môi trường này có thể mở rộng, tương tác, đa năng và kết hợp các công nghệ sáng tạo cũng như mô hình tương tác giữa người tham gia ở cả cấp độ cá nhân và doanh nghiệp.
# Mối quan hệ NFT và Metaverse
- Nền kinh tế mở và công bằng
```
    Người dùng và doanh nghiệp có thể chuyển các tài sản và dịch vụ trong thế giới thực vào một môi trường phi tập trung ảo được gọi là metaverse. Một cách thức để mời gọi nhiều tài sản trong thế giới thực hơn vào metaverse là sử dụng các mô hình chơi game sáng tạo kết hợp với các trò chơi blockchain có thể tương tác.

```
- Quyền sở hữu tài sản
```
    Với NFT, người dùng có thể toàn quyền sở hữu các vùng đất và không gian ảo của họ trong metaverse. Blockchain cơ bản cho phép người dùng chứng minh quyền sở hữu tài sản và phát triển bất động sản ảo của mình như mong muốn.
```
# Ứng dụng NFT
- Vay thế chấp NFT : https://drops.co/
- Tạo bộ suu tập độc nhất 
- Mua bán đất ảo 
- Lưu trữ thông tin 

# ERC
- Tiêu chuẩn cho các token phải tuần theo 
- ERC721: 
    - tiêu chuẩn này nhằm mục đích tạo ra các token có thể hoán đổi cho nhau
    - Token trong ERC 721 là duy nhất và đại diện cho một tài sản duy nhất
- ERC1155:
    - Mục tiêu là tạo ra một giao diện hợp đồng thông minh có thể đại diện cho cả SFT và NFT
    - Chuyển Tiền Hiệu Quả: có thể chọn chuyển nhiều token trong cùng một hoạt động. Nó không chỉ làm giảm chi phí giao dịch mà còn giảm thiểu tác động đến network.
    - Nhiều Tokens Trong 1 Hợp Đồng Duy Nhất
- Khác biệt: 
    -  tiêu chuẩn ERC-721 chỉ tạo ra NFT và buộc các nhà phát triển phải tạo một hợp đồng thông minh cho mỗi token
    - ERC-1155 cho phép các nhà phát triển phát triển một hợp đồng thông minh duy nhất có thể được sử dụng để tạo các token hoặc NFT
    -  Vì ERC-721 cho phép thực hiện một thao tác duy nhất nên mỗi giao dịch rất tốn kém và mất thời gian
    - ERC-1155 cho phép thực hiện nhiều thao tác trong một giao dịch nên nó rẻ hơn và hiệu quả hơn
