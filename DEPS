# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6cfcfaf1985a765c1691f12d413a2fd2945e918f',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'd554b6eb885b8b4ebadbad08dec684900e840479',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b824a462d4256d720bebb40e78b9eb8f78bbb305',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '971a7b6e8d7740035bbff089bbbf9f42951ecfd5',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '65586d13fb197279942581ba9c2eb2c6b664487c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '65e5428032e4ccb2e064fa8691b96e61701d5956',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2a3347d5e74d359e3ecb8e229917f3335bfa2dfa',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9aa2c08f82e3fb18d43e37e44015a79af7f3b672',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'adaf05f2bac929393a859eda1644b5a38cfd06c1',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
