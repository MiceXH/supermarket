# supermarket
仓库类 Warehouse{

	仓库编号 long whID;
	仓库管理员编号 staff whAdminID;
	仓库名 whName;
	仓库地址 whAddress;
	仓库容量 capacity;
	仓库剩余容量 leftCapacity;

}

采购类 Purchase{

	采购编号 pchID;
	采购金额 pchMoney;
	采购日期 pchDate;
	采购员编号 pcherID;
	供应商编号 Supplier supID;
}
