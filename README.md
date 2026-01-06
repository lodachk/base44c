# base44c
Monitoring Failed Approvals
if receipt.status == 0 and "approve" in tx["input"]:
    print("Approval failed")
