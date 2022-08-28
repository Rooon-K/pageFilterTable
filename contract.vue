<template>
  <PFTable
    tittle="查询"
    :tableColumn="tableColumn"
    :tableData="tableData"
    :pageSize="5"
  ></PFTable>
</template>

<script>
import PFTable from "../pageFilterTable.vue";
export default {
  name: "table",
  components: {
    PFTable,
  },
  data() {
    return {
      tableData: [
        {
          identity: "12987122",
          name: "好滋好味鸡蛋仔0",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻1",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987123",
          name: "好滋好味鸡蛋仔1",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987123",
          name: "好滋好味鸡蛋仔1",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987123",
          name: "好滋好味鸡蛋仔1",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987123",
          name: "好滋好味鸡蛋仔1",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987123",
          name: "好滋好味鸡蛋仔1",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987123",
          name: "好滋好味鸡蛋仔1",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987123",
          name: "好滋好味鸡蛋仔1",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987123",
          name: "好滋好味鸡蛋仔1",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987124",
          name: "好滋好味鸡蛋仔2",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987125",
          name: "好滋好味鸡蛋仔3",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987126",
          name: "好滋好味鸡蛋仔4",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987127",
          name: "好滋好味鸡蛋仔5",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987128",
          name: "好滋好味鸡蛋仔6",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987129",
          name: "好滋好味鸡蛋仔7",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987130",
          name: "好滋好味鸡蛋仔8",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987131",
          name: "好滋好味鸡蛋仔9",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987132",
          name: "好滋好味鸡蛋仔10",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
        {
          identity: "12987133",
          name: "好滋好味鸡蛋仔11",
          category: "江浙小吃、小吃零食",
          desc: "荷兰优质淡奶, 奶香浓而不腻",
          address: "上海市普陀区真北路",
          shop: "王小虎夫妻店",
          shopId: "10333",
        },
      ],
      tableColumn: [
        {
          label: "商品名称",
          value: "name",
          isShow: true,
          filters: [
            { text: "好滋好味鸡蛋仔0", value: "好滋好味鸡蛋仔0" },
            { text: "好滋好味鸡蛋仔1", value: "好滋好味鸡蛋仔1" },
          ],
          filterVal: [
            "好滋好味鸡蛋仔0", "好滋好味鸡蛋仔1"
          ]
        },
        {
          label: "所属店铺",
          value: "shop",
          isShow: false,
        },
        {
          label: "商品 Id",
          value: "identity",
          isShow: true,
          filters: [
            { text: "12987122", value: "12987122" },
            { text: "12987123", value: "12987123" },
          ],
          filterVal: [
            "12987122", "12987123"
          ]
        },
        {
          label: "店铺 Id",
          value: "shopId",
          isShow: false,
        },
        {
          label: "商品分类",
          value: "category",
          isShow: false,
        },
        {
          label: "店铺地址",
          value: "address",
          isShow: false,
        },
        {
          label: "商品描述",
          value: "desc",
          isShow: true,
          filters: [
            { text: "荷兰优质淡奶, 奶香浓而不腻", value: "荷兰优质淡奶, 奶香浓而不腻" },
            { text: "荷兰优质淡奶,奶香浓而不腻1", value: "荷兰优质淡奶, 奶香浓而不腻1" },
          ],
          filterVal: [
            "荷兰优质淡奶, 奶香浓而不腻","荷兰优质淡奶, 奶香浓而不腻1",
          ]
        },
      ],
    };
  },
};
</script>
