# supermarket
仓库类 Warehouse{

	仓库编号 long whID;
	仓库管理员编号 Staff whAdminID;
	仓库名 whName;
	仓库地址 whAddress;
	仓库容量 capacity;
	仓库剩余容量 leftCapacity;

}

采购类 Purchase{

	采购编号 pchID;
	采购金额 pchMoney;
	采购日期 pchDate;
	采购员编号 Staff pcherID;
	供应商编号 Supplier supID;
}

出库类 Exit{

	出库表编号 exitID;
	仓库管理员编号 Warehouse whAdminID;
	超市编号 Supermarket smID;
	商品编号 Product pID;
	仓库编号 Warehouse whID;
	出库日期 exitDate;
	出库数量 exitNum;
}
