# Bai 2: Quan ly nhanh va giai quyet Merge Conflict

## Gioi thieu

Dong noi dung chung: Nhanh main da cap nhat README va tinh nang moi tu nhanh feature-update da duoc hop nhat.

## Bao cao

### Cac buoc da thuc hien

1. Khoi tao Git repository trong thu muc `homework/session_04/ex2`.
2. Cau hinh danh tinh tac gia o cap local bang `git config --local`.
3. Tao commit ban dau tren nhanh `main`.
4. Tao nhanh moi bang lenh `git switch -c feature-update`.
5. Sua dong noi dung chung trong `README.md` tren nhanh `feature-update` va commit.
6. Quay lai nhanh `main`, sua cung dong trong `README.md` theo noi dung khac va commit.
7. Chay `git merge feature-update` de co y tao merge conflict.
8. Mo file `README.md`, xu ly thu cong cac marker conflict do Git chen vao file.
9. Dua file da giai quyet conflict vao staging area va tao merge commit.

### Noi dung xung dot da duoc xu ly

Dong xung dot cuoi cung duoc hop nhat thanh:

```text
Dong noi dung chung: Nhanh main da cap nhat README va tinh nang moi tu nhanh feature-update da duoc hop nhat.
```

### Lenh kiem tra lich su nhanh

```bash
git log --graph --oneline
```

Ket qua:

```text
*   ab75df2 Merge feature-update and resolve README conflict
|\  
| * f987061 Update README on feature branch
* | 8e745fa Update README on main branch
|/  
* 19bbecb Initial README for branch exercise
```
