自定义布局
Room 持久化库


1. Android 网络请求框架​
- OkHttp：掌握 OkHttp 的基本使用，如创建 OkHttpClient 实例，构建 Request 对象（包括设置请求方法、URL、请求头等），通过 Call 发起请求并在回调中处理响应结果。了解 OkHttp 的拦截器（Interceptor）的使用，可用于日志记录、请求参数添加等功能。​
- Retrofit：它是一个类型安全的 HTTP 客户端，基于 OkHttp 实现。熟悉如何定义 Retrofit 接口（使用注解来描述请求，如 @GET、@POST 等），创建 Retrofit 实例并通过接口实例发起网络请求，处理响应数据（如使用 GsonConverterFactory 将 JSON 数据转换为 Java 对象）。