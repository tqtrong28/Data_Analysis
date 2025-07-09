# Data_Analysis


Pandas là một thư viện trong Python với ưu điểm là nhanh, mạnh, linh động, dễ sử dụng, mã nguồn
mở, công cụ dùng để phân tích và thao tác dữ liệu. Pandas được xây dựng trên thư viện NumPy và
có nhiều functions hỗ trợ cleaning, analyzing, và manipulating data, có thể giúp ta extract valuable
insights của các tập dữ liệu. Pandas rất hiệu quả khi sử dụng trên dữ liệu bảng, như SQL table hoặc
Excel spreadsheets.


Một số đặc điểm của Pandas:
• Thao tác với các nguồn dữ liệu từ file csv, excel file, SQL, JSON file.
• Cung cấp các loại cấu trúc dữ liệu khác nhau như Series, DataFrame và Panel.
• Có thể đáp ứng nhiều dạng dataset khác nhau như time series, heterogeneous data, tabular và
matrix data.
• Có thể làm việc với missing data bằng cách xóa chúng hoặc gán cho chúng giá trị zeros hoặc giá
trị phù hợp với trạng thái test.
• Có thể dùng cho việc parsing và conversion data.
• Cung cấp các kỹ thuật lọc dữ liệu.
• Cung cấp time series functionality – date range generation, frequency conversion, moving window
statistics, data shifting và lagging.
• Tích hợp tốt với các thư viện khác của Python như Scikit-learn, statmodels và SciPy.
• Có hiệu năng cao.


Một số function trên Pandas thường dùng để xử lý dữ liệu:
• Handle missing values: isna(), notna() – tìm kiếm các giá trị NA, isnull().
• Indexing and slicing in Pandas: .loc (label based), .iloc (integer based), .ix (label and integer
based).
• Các query như trong excel hay SQL: where(), query().
• Sort: sort_index(), sort_values().
• Series basic functionality: axes, dtype, empty, ndim, size, values, head(), tail().
• Dataframe basic functionality: T, axes, dtypes, empty, ndim, shape, size, values, head(), tail().
• Các function liên quan thống kê: count(), sum(), mean(), median(), model(), std(), min(),
max(), abs(), prod(), cumsum(), cumprod(), describe(), ptc_change(), cov(), corr(), rank(), var(),
skew(), apply().
• Các function filter data: groupby(), get_group(), merge(), concat(), append(), melt(), pivot(),
pivot_table().

• Một số function khác: get_option(), set_option(), reset_option(), describe_option(), op-
tion_context().
