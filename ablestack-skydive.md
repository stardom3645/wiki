# ABLESTACK-Skydive

ABLESTACK-Skydive�� �ǽð� ��Ʈ��ũ �������� �� �������� �м���ν� ��Ʈ��ũ �����󿡼� �Ͼ�� ���� ���������� �����ϴ� ����� �����ϴ� ���� ��ǥ�� �մϴ�.


ABLESTACK-Skydive�� ������Ʈ�κ��� ��Ʈ��ũ �̺�Ʈ�� �����Ͽ� ��Ʈ��ũ ���������� ǥ���մϴ�.

![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-ui-main.png?raw=true)

## Key features

* ��Ʈ��ũ �������� �� flows ĸó
* VM ������ ����
* ��Ÿ������ �˻��� ���� ���̶���Ʈ ���


## Tutorials

 - �����ϱ�
   - �� UI
     - ABLESTACK-Skydive�� ��ġ�� �Ϸ�� �� ��Ʈ 8082�� ���� Web UI�� ����� �� �ֽ��ϴ�. �� ���������� http://{mold�� ipv4 �ּ�}:8082�� �����ϸ� ���������� ��Ÿ���ϴ�.
   - �������� ȭ�� ����
     - ���������� �������� ���еǾ� ������ ���(Node)���� �ش�Ǵ� ������ ������ �׷����·� ��ġ�� �ֽ��ϴ�.
     - ���(Node)���� ����� ����(Edge)�� ǥ�õǸ� Ownership ���踦 ǥ���ϰų� ������ �帧�� ��Ÿ���ϴ�.
     - ��������� ��Ÿ�����͸� Ȯ���ϴ� ����� ��� �� ������ Ŭ���� ��� �������� �������� Ȯ���� �� �ֽ��ϴ�.
   - ��Ʈ��ũ ���� ����
     - ABLESTACK-Skydive Agent�� �� ��Ʈ��ũ ������ �����ϴ� ���� Probe�� �̷���� ������ �⺻������ NetLINK, LibVirt, LLDP, Socket Information Probe�� Ȱ��ȭ �Ǿ��ֽ��ϴ�.
     - NetLINK Probe�� ���� ��Ʈ��ũ ������ ������Ʈ �ֱ�� 30���Դϴ�.
     - ����ġ�� ������ LLDP Probe�� ���� �����Ǵµ� ���� ����ġ���� LLDP ����� Ȱ��ȭ �Ͽ��� �մϴ�. ����ġ�� LLDP ������ �۽��ϸ� ABLESTACK-Skydive�� Probe�� �� Host�� ��ġ�� "lldpd ��Ű��"�� Ȱ���Ͽ� ������ �����մϴ�.

 - Ʈ���� ĸó
   - ĸó�� ���۵Ǹ� ĸó�� �������̽��� ĸó�� Ȱ�� �������� ��Ÿ���� 'ī�޶� ���'�� ǥ�õ˴ϴ�.
   ![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-capture-camera.png?raw=true)
   - ĸó�� �����ϱ� ���ؼ��� �ش� ��带 ������ ���콺�� Ŭ���Ͽ� "Capture"�� �����ϰų� ���� ��ܿ� ��ġ�� "ī�޶� ���"�� Ŭ���Ͽ� �����մϴ�.
   ![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-capture-mouse-click-button.png?raw=true)
   ![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-capture-button.png?raw=true)
   - ĸó�� �� �� �ִ� ��� ������ �ֽ��ϴ�. Node�� Ÿ���� device, bridge, vlan�� ��� ĸó ����� Ȱ��ȭ �� �� �ֽ��ϴ�.
   - ĸó ������ ĸó�� Ȱ��ȭ�� ��带 ������ ���콺�� Ŭ���Ͽ� "Delete Captures"�� �����ϰų� UI ������ �ִ� ���ڵ�� �޴� �� "Captures"�� Ŭ���� �� ������ ĸó�� �����Ͽ� �����մϴ�. ĸó�� �������� �ʰ� ��Ʈ��ũ ������ ����Ǿ� ���񽺸� ������� ��� Error �޽����� �߻��� �� �����Ƿ� ������� �ʴ� ĸó�� ������ �����Ǿ�� �մϴ�.
   
- Flow table
    - ĸó�� ���������� Ȱ��ȭ�Ǹ� ���� ���ڵ�� �޴��� Flow table�� ��Ÿ���ϴ�.
    - Flow table�� �ε��Ǵ� �� �������� ���� 10�� �̻��� �ð��� �ɸ��� ��쵵 �ֽ��ϴ�.
    - Flow table �޴� ��ܿ� "View Columns"�� Ŭ���ϸ� ���̺� ǥ���� �÷��� ������ �� �ֽ��ϴ�.
    - Flow table�� ��� ���� Flow table�� ���� ĸó Ȱ��ȭ�� ��Ʈ��ũ(Network A)���� Network B ������ ���� Ȯ�� �Ǵ� ������ �̵��� ���� Ȯ���� �� �ֽ��ϴ�.

    ![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-flowTable.png?raw=true)


