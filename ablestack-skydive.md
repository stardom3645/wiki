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
     - ���������� �������� ���еǾ� ������ ���(Node)���� �ش�Ǵ� ������ �׷����·� ��ġ�� �ֽ��ϴ�.
     - ���(Node)���� ����� ����(Edge)�� ǥ�õǸ� Ownership ���踦 ǥ���ϰų� ������ �帧�� ��Ÿ���ϴ�.
     - ��������� ��Ÿ�����͸� Ȯ���ϴ� ����� ��� �� ������ Ŭ���� ��� UI�� �����ʿ��� Ȯ���� �� �ֽ��ϴ�.
   - ��Ʈ��ũ ���� ����
     - ABLESTACK-Skydive Agent�� �� ��Ʈ��ũ ������ �����ϴ� ���� Probe�� �̷���� ������ �⺻������ NetLINK, LibVirt, LLDP, Socket Information Probe�� Ȱ��ȭ �Ǿ��ֽ��ϴ�.
     - NetLINK Probe�� ���� ��Ʈ��ũ ������ ������Ʈ �ֱ�� 30���Դϴ�.
     - ����ġ�� ������ LLDP Probe�� ���� �����Ǵµ� ���� ����ġ���� LLDP ����� Ȱ��ȭ �Ͽ��� �մϴ�. ����ġ�� LLDP ������ �۽��ϸ� ABLESTACK-Skydive�� Probe�� �� Host�� ��ġ�� "lldpd ��Ű��"�� Ȱ���Ͽ� ������ �����մϴ�.

 - ĸó
   - ĸó�� ���۵Ǹ� ĸó�� �������̽��� ĸó�� Ȱ�� �������� ��Ÿ���� 'ī�޶� ���'�� ǥ�õ˴ϴ�.
   - ĸó�� �����ϱ� ���ؼ��� �ش� ��带 ������ ���콺�� Ŭ���Ͽ� "Capture"�� �����ϰų� ���� ��ܿ� ��ġ�� "ī�޶� ���"�� Ŭ���Ͽ� �����մϴ�.
   - ĸó�� �� �� �ִ� ��� ������ �ֽ��ϴ�. Node�� Ÿ���� device, bridge, vlan�� ��� ĸó ����� Ȱ��ȭ �� �� �ֽ��ϴ�.
   - ĸó ������ ĸó�� Ȱ��ȭ�� ��带 ������ ���콺�� Ŭ���Ͽ� "Delete Captures"�� �����ϰų� UI ������ �ִ� ���ڵ�� �޴� �� "Captures"�� Ŭ���� �� ������ ĸó�� �����Ͽ� �����մϴ�. ĸó�� �������� �ʰ� ��Ʈ��ũ ������ ����Ǿ� ���񽺸� ������� ��� Error �޽����� �߻��� �� �����Ƿ� ������� �ʴ� ĸó�� ������ �����Ǿ�� �մϴ�.
   
- Flow table
    - ĸó�� ���������� Ȱ��ȭ�Ǹ� ���� ���ڵ�� �޴��� Flow table�� ��Ÿ���ϴ�.
    - Flow table�� �ε��Ǵ� �� �������� ���� 10�� �̻��� �ð��� �ɸ��� ��쵵 �ֽ��ϴ�.
    - Flow table �޴� ��ܿ� "View Columns"�� Ŭ���ϸ� ���̺� ǥ���� �÷��� ������ �� �ֽ��ϴ�.
    - Flow table�� ��� ���� Flow table�� ���� ĸó Ȱ��ȭ�� ��Ʈ��ũ(Network A)���� Network B ������ ���� Ȯ�� �Ǵ� ������ �̵��� ���� Ȯ���� �� �ֽ��ϴ�.

## Get involved

* Weekly meeting
    * [General - Weekly meeting](https://meet.jit.si/skydive-project) - every Thursday at 5:00 - 5:30 PM CET ([Calendar](https://calendar.google.com/calendar/u/2?cid=c2t5ZGl2ZXNvZnR3YXJlQGdtYWlsLmNvbQ))
    * [Minutes](https://docs.google.com/document/d/1eri4vyjmAwxiWs2Kp4HYdCUDWACF_HXZDrDL8WcPF-o/edit?ts=5d946ad5#heading=h.g8f8gdfq0un9)

* Slack
    * Invite : https://slack.skydive.network
    * Workspace : https://skydive-project.slack.com

## Contributing

Your contributions are more than welcome. Please check
https://github.com/skydive-project/skydive/blob/master/CONTRIBUTING.md
to know about the process.

## License

This software is licensed under the Apache License, Version 2.0 (the
"License"); you may not use this software except in compliance with the
License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
