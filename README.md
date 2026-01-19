``` mermaid
flowchart TD
    A[Bắt đầu] --> B[Khách hàng đến / yêu cầu đặt phòng]

    B --> C[Nhập thông tin Customer]
    C --> D[Chọn RoomType]
    D --> E{Room còn trống?}

    E -- Không --> D
    E -- Có --> F[Tạo Booking]

    F --> G[Cập nhật trạng thái Room = Not Available]
    G --> H[Khách Check-in]

    H --> I{Sử dụng dịch vụ?}
    I -- Có --> J[Ghi ServiceUsage]
    J --> I
    I -- Không --> K[Khách Check-out]

    K --> L[Tạo Invoice]
    L --> M[Tính roomCost + serviceCost]
    M --> N[Tổng totalAmount]

    N --> O[Thanh toán Payment]
    O --> P{Thanh toán thành công?}

    P -- Không --> O
    P -- Có --> Q[Cập nhật Booking = Checked-out]
    Q --> R[Cập nhật Room = Available]
    R --> S[Kết thúc]
