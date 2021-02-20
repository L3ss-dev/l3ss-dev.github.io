## Kerberos

### 3 roles:
- Client
- KDC (Key Distribution Center)
- Service

### Request Process
1. Client --> KDC (Authentication Service)
2. Client <-- KDC (Authentication Service)
3. Client --> KDC (Ticket Granting Service = TGS)
4. Client <-- KDC (TGS)
5. Client --> Service
6. Client <-- Service