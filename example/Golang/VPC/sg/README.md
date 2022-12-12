## 首云·openapi调用示例

使用说明：

1. 安全组配额：每个客户在一个区域内（region）可创建20个安全组，一个安全组可创建100条规则，一个实例最多绑定5个安全组，若需提升配额，联系对接人；
2. 当一个实例（云主机）绑定了安全组后，若此实例（云主机）有且只有这一个安全组，此安全组无法解绑；
3. 当实例（云主机）删除时，因现版本云主机侧未对接安全组，故请客户删除云主机后，联系对接人去后台此删除实例下所有安全组。云主机删除且解绑安全组的功能后续增加；
4. 用户在调用ecs安全组所有openapi接口时，建议留存每次请求返回的`RequestId`，若调用出现问题，方便拿`RequestId`找对接人排查问题；
5. 请关注接口文档中`注意`里面的说明，有助于开发效率；
6. 若安全组未配置任何规则，则该安全组启动默认规则：入站全拒绝，出站全允许；
7. 在配置规则端口号（Port）时，暂时尽量不要配置大范围的端口区间（例如：1/10000），这样安全组规则生效性能会较差。建议端口号在100个以内，此问题后续会优化。